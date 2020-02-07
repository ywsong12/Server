## Window 환경에서 다른 서버로의 Syslog 전송을 위한 방법
### Window 자체에서는 다른 서버로 Syslog를 보낼 수 가 없어서 Agent를 사용하여야 한다.
1. SyslogAgent 설치 후 관리자권한으로 SyslogAgentConfig.exe 실행
2. Syslog 전송할 서버 IP 입력
3. Install 클릭 후 Start Service 클릭하여 Syslog 전송
