## Git Command

- `git init`

  - git을 초기화하는 명령어를 사용하여 원격과 로컬 파일을 git 을 통해 연동한다.

- `git remote add origin <remote repository url>`

  - 원격 리포지토리의 주소를 로컬로 가지고 와서 origin이라는 이름에 저장한다.

- `git add <file name>`
  - 변동사항이 생긴 파일을 커밋할 파일 목록에 올린다.
- `git commit`
  - 파일을 커밋한다. -m 를 사용해서 관련 정보를 메세지에 담아서 추가된 사항을 함께 커밋한다.
- `git push origin <branch name>`
  - origin이라고 저장된 원격 저장소의 특정 브랜치에 로컬의 변동사항을 보낸다.
- `git pull origin <branch name>`
  - 원격 저장소의 특정 브랜치에 저장된 파일들을 로컬 저장소에 가지고 온다.
- `git merge <branch name>`
- main과 특정 branch를 병합한다.
