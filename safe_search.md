# Windows
#### Windows에서 Windows 키를 누르고 메모장이라고 입력합니다.
#### 메모장을 마우스 오른쪽 버튼으로 클릭하고 Run as Administrator(관리자 권한으로 실행)를 선택합니다.
#### Windows에서 이 프로그램을 변경할지 묻는 경우 Yes(예)를 클릭합니다.
#### 메모장에서 호스트 파일을 엽니다. 대부분의 Windows 설치 시 이 파일은 C:\Windows\System32\drivers\etc\hosts에 위치합니다.
#### Windows 키를 누르고 cmd라고 입력한 다음 Enter 키를 누르면 명령 프롬프트가 열립니다.
#### ping forcesafesearch.google.com 명령어를 입력하고 IP 주소를 기록합니다. IP 주소의 형식은 다음과 같습니다. 216.239.38.120
#### 기록해 두었던 IP 주소로 호스트 파일 마지막 부분에 새 항목을 작성합니다. 예: 216.239.38.120 www.google.com #forcesafesearch.
#### 중요: www.google.co.uk와 같이 사용자가 이용할 수 있는 다른 Google 국가 도메인에 이 행을 복사하세요.
#### 호스트 파일을 저장합니다.
#### 세이프서치가 사용 설정되어 있는지 확인하려면 google.com으로 이동하여 세이프서치가 기본으로 사용 설정되어 있으며 중지할 수 없는지 확인하세요.

#### 참고: Windows가 PC의 다른 위치에 설치된 경우 명령 프롬프트에 cd /d %systemroot%\system32\drivers\etc 명령어를 입력하면 호스트 파일을 찾을 수 있습니다.

# linux
터미널을 엽니다.
ping forcesafesearch.google.com 명령어를 입력하고 IP 주소를 기록합니다. IP 주소의 형식은 다음과 같습니다. 216.239.38.120
sudo nano /etc/hosts 명령어를 입력합니다.
기록해 두었던 IP 주소로 호스트 파일 마지막 부분에 새 항목을 작성합니다. 예: 216.239.38.120 www.google.com #forcesafesearch.
중요: www.google.co.uk와 같이 사용자가 이용할 수 있는 다른 Google 국가 도메인에 이 행을 복사하세요.
호스트 파일을 저장합니다.
세이프서치가 사용 설정되어 있는지 확인하려면 google.com으로 이동하여 세이프서치가 기본으로 사용 설정되어 있으며 중지할 수 없는지 확인하세요.

