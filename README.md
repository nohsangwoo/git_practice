#git-practice

깃 공부

oct에서 push

#소스트리 설치
https://www.sourcetreeapp.com/
bitbucket아이디로 로그인 #이후 소스트리프로그램으로 git 프로젝트 열기

#branch 만들기
git branch cat
//cat이라는 이름의 branch를 만들어라

#branch이동하기
git checkout cat
cat이라는 읾의 branch로 이동하라

그럼 기존의 head인 master branch에서 cat branch로 head가 이동됨

#다른 협업자도 각자의 branch를 만들어서 평행세계를 만들어둠
이후 다른 협업자들은 git pull 시도후

소스트리 좌측하단의 원격 하위 카테고리에서 다른 branch를 가져올수있음

#merge 합치기
git merge orc
//git merge 브랜치이름
