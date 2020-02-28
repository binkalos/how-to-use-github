# how-to-use-github
### 기본적인 git 사용법!!
1. 내 로컬 저장소(폴더)에서 `git init` 하기
1. 깃허브 들어와서 repository 만들기
1. repository 주소 복사한 뒤에 `git remote add origin 레파지토리주소` 하기
1. `git status`로 파일 목록 빨간 글씨로 뜨는지 확인하기
1. `git add .`해서 모든 파일 올릴 준비(스테이징)하기
1. `git commit -m "하고 싶은 말"` 쓰고 커밋하기
1. `git push origin master` 하기  
만약 저기서 오류가 나면 `git pull origin master` 해보기(github 사이트에서 뭘 바꿨으면 항상 해 줘야 함!!)   
`git pull origin master` 에서도 오류가 난다면 `git pull origin master --allow-unrelated-histories` 한 후    
`git add .` -> `git commit -m "메세지"` -> `git push origin master`하기

이건 첫 커밋 할 때만 1번부터 쭉 하면 되고, 다음 커밋부터는 `git add` 부터 하면 됨!!

### 만약 저게 안 되는 상황에는?!
1. 깃허브 들어와서 repository 만들기
1. 바탕화면 등 적당한 로컬 폴더에서 `git clone 레파지토리주소` 하기
1. 올려야 하는 파일 git clone한 폴더(위 상황에서는 바탕화면)에 다 복사 붙여넣기
1. `git add .` 부터 하면 됨!
