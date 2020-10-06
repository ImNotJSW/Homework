#Git 명령어
## 해달 부트캠프 과정에서 배운 것 위주로 기술

1. `git init`
    + 처음 Git을 사용할 때 쓴다.
2. `git status`
    + __무엇이 연동되었는지__ 보여준다.
3. `git add [파일 이름]`
    + Git이 추적하는 파일로 추가한다.
    + 모든 파일에 적용 하려면, `.과 *`을 사용한다.
4. `git config --global user.email "깃허브 이메일"`
    + 깃에 연동할 이메일 계정 설정
5. `git config --global user.name "깃허브 닉네임"`
    + 깃에 연동할 닉네임 설정
6. `git commit -m '설명'`
    + 현재 변경 사항을 저장한다.
7. `git log`
    + 작성자, 일자, 설명 등을 보여준다.
    + `--stat`옵션을 사용하면, 안에 있는 파일도 보여준다.
8. `git reset HEAD^`
    + 가장 최근 commit을 없애고 이전으로 돌아간다.
    + `HEAD^` 앞에 `--hard` 옵션을 사용하면 commit 내역도 사라진다.
9. `git remote add [원격 저장소 별명][원격 저장소 URL]`
    + 원격 저장소를 설정한다.
10. `git remote remove [원격 저장소 별명]`
    + 해당 원격 저장소를 선택 해제한다.
11. `git remote -v`
    + 현재 설정된 원격 저장소 목록을 보여준다.
12. `git push [원격 저장소 별명] [branch]`
    + 원격 저장소에 업로드한다.
  