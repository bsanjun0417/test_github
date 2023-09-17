# test_github.github.io
깃허브 연습

push가 업로드 하는거

## git init 깃을 쓸 준비하는거임 초기화 함
맨처음에프로젝트 올리때 해주면됨
## git add . 점은 전부다
add 는 올릴 파일거 선택 .하면 전부 올린다
## git add index.html 이러면 html만 올린다
node모듈같은거 제외하고 올리는게 나으니까 깃헙에 이런느낌인건가 확인하셈 나중에 자동으로 제외하고 올라가는건가?


## git status 추가한거 상태 알려주는거임


## git commit
히스토리 만들어준다  m은 메시지줄임말 
## git commit -m "커밋 이름(제목짓는것)"

## 깃허브 사이트에서 레포지터리 만든거에서 이걸 로컬에 연결해준다 깃허브와 내가 만든 로컬 파일이 연결되어짐
## git remote add origin https://github.com/bsanjun0417/test_github.git
(깃허브에 배포연결되는거임)

## git remote -v
연결됬는지 나옴 

배포한후 새로 수정할게 있다면 git init은 다시 할 필요없음
git add .하면 다시 수정한게 업로드됨 status에
git status에 수정된게 잡힘

아까와 다른 수정본이 히스토리 공간을 만들어야됨
첫번째결과물 두번째 수정본 결과물 이렇게 만드는거지
그리고 git push origin main(브랜치)
하면 다시 업로드됨

https://hackmd.io/@oW_dDxdsRoSpl0M64Tfg2g/ByfwpNJ-K
이거 참고자료

settings에서 pages메뉴 클릭
깃허브 액션은 ci cd관련
deploy from branch는 브랜치로 배포
