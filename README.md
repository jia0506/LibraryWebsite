# LibraryWebsite

## GitBash 실행 방법
1. **오른쪽 클릭:** 원하는 폴더나 디렉토리에서 마우스 오른쪽 버튼을 클릭합니다.
2. **추가 옵션 표시:** 나오는 메뉴에서 "Git Bash Here" 옵션을 선택하여 GitBash 창을 엽니다.

## Repository Clone (복제)
1. **링크 카피:** GitHub 페이지에서 복제하고자 하는 프로젝트의 주소를 복사합니다.  
https://github.com/jia0506/LibraryWebsite.git
2. **Git Bash 켜기:** 위에서 설명한 방법으로 Git Bash 창을 엽니다.
3. **Clone 명령어 실행:** Git Bash 창에 다음 명령어를 붙여넣고 실행합니다.  
$ git clone https://github.com/jia0506/LibraryWebsite.git

## Git 동기화 (Pull)
1. **Git Bash 열기:** 이미 열려있는 Git Bash 창을 사용합니다.
2. **Pull 명령어 실행:** 프로젝트 폴더로 이동 후 다음 명령어를 실행하여 원격 저장소의 변경사항을 가져옵니다.  
$ git pull

## Git 업로드 (Push)
1. **Git Bash 열기:** 이미 열려있는 Git Bash 창을 사용합니다.
2. **변경 사항 추가:** 프로젝트 폴더에서 작업을 마친 후 모든 변경 사항을 추가합니다.  
$ git add .
3. **커밋:** 변경 사항을 커밋하고 설명 메시지를 추가합니다.  
$ git commit -m "표시하고 싶은 메세지"
4. **푸시:** 변경 사항을 원격 저장소에 업로드합니다.  
$ git push
