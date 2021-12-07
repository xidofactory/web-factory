# web-factory

### 깃 commit 처리시 작성하는 내용

``` shell
[글머리] 작성된 data요약 (file명) :글머리 표현아이콘: 설명 (이슈파트 위치)
```



#### 앞 글머리로 붙이는 형태

- feat : 새로운 기능에 대한 커밋 

- fix : 버그 수정에 대한 커밋 

- build : 빌드 관련 파일 수정에 대한 커밋 

- chore : 그 외 자잘한 수정에 대한 커밋 

- ci : CI관련 설정 수정에 대한 커밋 

- docs : 문서 수정에 대한 커밋 

- style : 코드 스타일 혹은 포맷 등에 관한 커밋 

- refactor :  코드 리팩토링에 대한 커밋 

- test : 테스트 코드 수정에 대한 커밋

---

### 중간 아이콘처리

- 새로운문서 또는 세팅 `:new: `:new: 
- 단계별 체크 `:ab:` :ab: 
- 긴급 수정(오탈자 등) `:ambulance:` :ambulance: 
- 웹 배포 및 웹 확인 테스트 `:airplane: ` :airplane:
- 이슈 발생으로 이전단계로 수정 `:arrow_backward: ` :arrow_backward: 
- doc 메모 `  :notebook:` :notebook:

---

#### 깃 명령어

- `git clone '주소'` : repository에 자료를 받아서 사용
- `git status` : 현재 작성중인 디랙토리 기준 내용 상태파악
- `git add [첨부파일]` : git으로 보낼 자료 선택
- `git commit -m '설명'` : 보낼 자료에대한 설명
- `git push` : 자료 전송
- `git push --origin-upstream` : 최초의 상태에서 자료를 본내는 경우 (브랜치를 생성하더라도 동일)
- `git pull` : 자료 추가로 받아오기
- `git branch -a` : branch 목록 받아오기(현재 디렉토리 뿐아니라, 서버의 자료까지 받아오는 것)
- `git checkout [브랜치명]` : 해당 브랜치로 이동
- `git checkout -b [브랜치명]` :현재 디렉토리에는 없으나 서버에 존재하는 자료를 받아오게 처리
- `git merge [브랜치명]` : 해당 branch를 병합 처리
- `git branch -d [브랜치명]` : 선택된 브랜치는 삭제 (local)
- `git push origin --delete [브랜치명]` : git 사이트에 존재하는 branch를 삭제
- `git reset HEAD~n` : git 현재내용을 이전 `n`단계만큼 이전상태로 이동 처리
- `git revert HEAD~n` : git reset과 유사하지만, `n`단계만큼 이전상태의 내용을 현재로 복사하여 가져오는 기능
- 

























