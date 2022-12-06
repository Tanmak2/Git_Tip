# Git_Tip

### 깃 연동
1. git init // git 저장소 생성
2. git add . // 저장소에 변경된 사항들을 스테이징 시키기 위함
             // waring 시 git config --global core.autocrlf true
3. git commit -m '커밋 메시지' // 스테이징된 파일들의 커밋 메시지 작성 및 커밋
4. git remote add origin 깃허브주소 // 최초 깃 레파지토리 주소 추가
5. git push origin main // 커밋 된 파일들 깃허브에 푸시
