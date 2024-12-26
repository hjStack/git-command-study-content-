
1. git init
-> git과 계약을 맺을때는 프로젝트의 최상위 프로젝트에서 git init
-> 그러면 git과 개발자는 협업관계가 시작된것임

2. 사용자 정보 등록
-> git config --global user.name hj
   
3. git의 세가지 영역과 git의 흐름
   1) working directory : 작업하고 있는 영역
    -> git add라는 명령어를 통해 working->staging으로 이동 
   2) staging directory : 리포지토리에 가기 전에 작업 내용을 모아두는 곳
    -> git commit라는 명령어를 통해 staging->Repository로 이동
    -> 깃의 작업 흐름에서 중간 역할을 하는 스테이징 영역은 커밋을 하기 전에 작업 내용을 저장하고 관리하는데 사용된다.
    스테이징 영역은 밑의 이유로 필요하다. 
      1. 변경사항을 따로 분리해서 관리 가능
      2. 변경사항을 검토하고 되돌릴 수 있다 ex) 장바구니에서 물건을 사지 않는 것으로 간주하고 상품을 다시 제자리로 두는 행위
   3) Repository : 깃과 관련된 모든 데이터가 이곳에 저장됨 

4. git commit
-> 커밋은 가능한 한 작은 단위로 분리하는 것이 좋음
-> ex) 장바구니에 담아놓은 상품들을 구매하는 행위와 비슷
