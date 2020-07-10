#### WMI(Windows Management Instrumentation)란?
###### 윈도우 리소스에 접근하여 여러가지 설정을 구성 가능하며, 파워쉘과 스크립트로 PC와 서버들을 로컬 원격 관리가 가능하게 해주는 윈도우 관리 도구이다.
1. WBEM과 CIM 의 표준 구현체이며, Windows 운영체제가 사용되는 환경에서의 자원에 대한 접근 및 관리를 하기위한 인프라 구조
2. 윈도우 리소스, 엑세스, 구성, 관리 및 모니터링이 가능하며, 스크립트 형식으로 시스템을 관리
3. 이벤트 로그 항목, 파일 시스템과 레지스트리 수정 및 기타 실시간 운영체제 변경 사항을 모니터링하며, 응답할 스크립트를 작성 가능
4. WMI는 namespace provider 하위에서 동작하며, 기본 root\cimv2에서 시작됨.(root\cimv2 에는 초기 네임스페이스의 다양한 정보들이 포함)
5. WMIC(Windows Management Instrumentation Command-line) 인터페이스 제공
