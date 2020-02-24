## Putty 활용한 ssh 키 생성 방법
1. putty 설치  
2. puttygne.exe 실행  
3. 'Generate' 버튼 클릭하여 키 생성  
4. 'Save public key' 버튼 클릭하여 공개키 저장(public_key명으로 저장)  
5. 'Save private key' 버튼 클릭하여 개인키 저장(private_key명으로 저장)  

### 리눅스 서버에 ssh 키 등록하여 접속하기
1. 접속할 리눅스 서버 계정에 접속    
2. 클라이언트에서 생성한 public_key 파일 내용을 복사하여 접속 서버계정 .ssh/authorized_keys 파일에 붙여넣기(authorized_keys파일 없을 시 생성)  
3. 클라이언트에서 putty실행하여 'Connection' 하위 'Data' 클릭 후 'Login details'에 접속 서버 계정을 입력  
4. 'SSH' 하위 'Auth' 클릭하여 'Private key file for authentication:' 에 생성해둔 private_key 파일을 넣기  
5. 'Session' 클릭 후 'Saved Sessions' 에 세션 명칭(ssh_key connect) 입력 후 우측 'Save' 클릭하여 저장  
6. 저장된 세션 명칭을 클릭하여 선택 후 접속 서버의 IP, Port 정보 입력 후 로그인 정보입력없이 접속되는지 확인  
