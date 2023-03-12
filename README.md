# task

## 과제방에 repo 주소로 업로드

1. task repository 포크로 본인 repository에 복사
2. 내려 받기해서 해당 README.md 문서 수정
3. 오늘까지 배운 git 내용 마크다운 형식으로 __잘__ 정리
  _markdown-cheetseat 참고_
4. 본인 repository에 업로드
5. 로컬 저장소 내용도 캡쳐해서 함께 업로드

이 아래로 내용 작성




- - - - 
## git 이란? ##

    파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템


## github 란? ##

    온라인 상에서 협업을 통해 버전 관리를 할 수 있게 해주는 대표적인 깃 호스팅 업체


## 명령어 정리 ##
   
<details>
<summary>#### git bash 명령어 ####</summary>
<p>
명령어  | 설명
------------- | -------------
pwd  | 현재 디렉토리 위치
clear  | 현재창에 보여진 입력한 것들과 출력된 것들을 화면에서 지움
cd 폴더명  | 입력한 폴더로 들어감
cd ..  | 현재 디렉토리에서 바로 상위 디렉토리로 이동
cd -  | 바로 이전 디렉토리로 이동
touch 파일명  | 파일 생성
rm 파일명  | 파일 삭제
</p>   
</details>

#### git의 자주쓰는 명령어 ####

명령어  | 설명
------------- | -------------
git add    | 파일 추가
git commit -m "파일 설명" | 커밋. 파일을 설명하는 메세지를 등록 (반드시 add 후에 등록)
git commit -am "파일 설명"  | 두번째 커밋부터 사용
git status  | 현재 상태 확인
git branch 브랜치명  | 브랜치 생성
git switch 브랜치명  | 원하는 브랜치로 이동
git branch -d 브랜치명  | 브랜치가 푸쉬되고 합쳐졌을때 삭제
git branch -D 브랜치명 | 브랜치 강제 삭제
git branch -a  |  모든 브랜치 확인 (*은 현재 위치)
git merge 브랜치명  | 현재 브랜치에서 원하는 브랜치 합침
git log  | 모든 커밋 이력 확인
git log --oneline  | 해당 라인 커밋 이력 확인
git log --oneline --all  | 해당 라인 커밋 이력 전부 확인
git rm 파일명  | 파일 삭제
git rm -r 디렉토리명  | 디렉토리 삭제
git rf 디렉토리명  | 파일이 남아 있어도 강제 삭제
git revert 0000000  | 복구하고자하는 커밋아이디로 복구 (파일을 복사하여 수정하여야함)



## github 사용하기 ##

<details>
  <summary>git과 github 연동하기</summary>   
   
  <p>1. github의 repositories탭에서 New를 선택하여 Create repository</p>
  <p>2. 화면에 나오는 git remote add origin 명령어와 url을 복사해서 bash창에 붙여넣기</p>
  <p>3. 팝업창의 sign in with your browser 클릭</p>
  <p>4. 옵션에서 전체 선택 후 authorize 버튼 클릭</p>
</details>
<details>
  <summary>github 사용하기</summary>   

  <p>1. git push -u origin main 명령어를 입력하여 파일을 푸쉬 (main : 브랜치명)</p>
  <p>2. git pull origin main 명령어를 입력하여 파일을 내려받기</p>
  <p>3. git clone http://~ 내 저장소로 복사 (폴더를 만든경우 한칸띄고 마침표 . )</p>
  <p>4. git remote rm origin 연결된 온라인 저장소 정보 삭제</p>
</details>
   
