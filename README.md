## 230823 ##
### 일반적인 사용 방법 ###
1. 로컬 저장소(숨김파일 .git) 생성 ->code($ git init)
2. README.md 파일 생성 -> git add . -> git commit -m "README.md 파일 생성" 
3. 온라인 저장소 생성 -> git remote add origin https://github.com/imsua1234/230823a.git(복붙)
-> git config --list를 통해 잘 등록 되어있는지 확인 -> git push -u origin main(복붙) -> 내용 추가하려면
commit -am " " 로 하기(하기 전에 꼭 메모장 저장하고) 그리고 또 git push를 통해 복붙하면 온라인 저장소에 생성
(push를 하기 전에는 로컬 저장소에만 생성)
4. README.md 파일 온라인 저장소에 업로드...

****
### gibhub에서 내려 받기 ###
`$ git pull origin main`

### clone과 pull 특징 ###
1. clone : 로컬에 저장소가 없는 경우. 저장소 자체를 복사
2. pull : 로컬에 연결된 저장소 있는 경우. 저장소 안에 있는 파일 내려받기

## 충돌(conflict)시 해결 방법 ##
__충돌 이유__
하나의 문서가 온라인과 로컬 각각 수정이 일어났기 때문

__해결방법__
1. 온라인 저장소와 로컬 저장소 내용이 다르므로 git pull origin main을 통해 로컬로 파일 내려받기
2. 받은 로컬 저장소의 문서를 수정 후 git commit -am " " 작성
3. git push -u origin main을 통해 온라인 저장소로 보냄



