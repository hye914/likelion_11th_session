1. workspace 디렉토리 생성
2. github repository 생성(협업 시 최상위 레포지토리 fork로 개인 레포지토리에 복사)
3. vscode로 workspace 열고 새 터미널 열고 git bash로 변경
4. git init 초기화
5. git clone <개인 레포지토리 url>
6. 작업할 디렉토리로 이동
7. git remote add origin <개인 레포지토리 url>
   git remote add upstream <협업 레포지토리 url>
   git remote -v로 확인 ... 
8. branch 생성 [git checkout -b 브랜치명, 생성과 이동 동시]
9. 파일 작업
10. git add . [작업한 파일 모두 add]
11. git commit -m "커밋내용"
12. git push origin <개인 브랜치명>
13. github 개인 레포지토리에 PR 
14. upstream에 pr요청
15. merge 되고 git pull upstream main
16. git checkout main
17. end