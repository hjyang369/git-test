## Git Command

- `git init`  
  git을 저장할 저장소를 만들어주는 명형어 반드시 git을 관리할 파일에서만 실행
  로컬에서 첫 시작 후 github에 push할 때 처음 한번만 사용
  만약 github에서 pull 받아온 내용이라면 안해도됨
- `git remote add origin <remote repository url>`
  로컬과 깃헙의 레파지토리 연결
- `git add <file name>`
  수정한 파일에 대한 이력을 남길 준비한다고 알려주는 명령어
- `git commit`
  수정한 파일에 대한 이력을 남기는 명령어
- `git push origin <branch name>`
  깃헙에 업로드를 하는 명령어
- `git pull origin <branch name>`
  깃헙의 특정 브랜치의 코드를 로컬로 가져오는 명령어
- `git merge <branch name>`
  로컬에서 현재 브랜치 코드와 특정 브랜치의 코드를 합치는 명령어
