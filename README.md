# Anti_Smishing_JeongHun_20174263

# 2022.05.02
- 이전 작업물 모두 제거 및 재시작.
- 기본적인 틀 체크.

# 2022.05.04
- SMS 권한 획득 및 읽기.
- SMS 수신시 받아오기 ( ~ing )

# 2022.05.10
- SMS 수신시 어플리케이션 강제종료 이슈
- 디자인과 SMSRECIEVER.java , SMSActivity.java 수정 및 작업중.

# 2022.05.16
- SmSActivity, MainActivity 통합.
- SmSReceiver activity_sms에서 sender, content 출력가능 (date 오류)
- 내일 content(sms parsing)에서 url parsing 및 미사용 코드 간소화.

# 2022.05.17
- SmSActivity 통합 후 제거
- 문자메시지 Content변수에 저장된 문자메시지 내용 url추출 메소드 추가 및 테스트 완료.

# 2022.05.31
- ApiExplorer 코드 전면 수정 및 정리.
- External libs 추가

# 2022.06.01 ~ 2022.06.15
- Notification class파일 제거 및 SmSReceiver통합.
- VirusTotal Api 최종 연동 확인 (Thread 활용).
- 미사용 코드 정리 및 통합.
- Min_SDK Version 23 -> 27 (*Android 8 Oreo 부터 Notification Channel use, Android 12 까지 대응 확인.)
- activity_main 메인화면만 간단 제작(사진 및 캡스톤디자인 조 소개)

# Known Issue
- 어플리케이션 강제종료 후 문자수신이 실행 오류발생.
- (Back_Ground 상태에서 테스트해야 정상적으로 Notification 푸쉬 확인 가능.)
- except, Working
