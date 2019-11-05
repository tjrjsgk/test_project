# 초기화
- git init 초기화 돼서 .git 디렉토리가 생성됨
# 파일 서버에 올리기 (push)
- git add 통해서 필요한 파일을 git 관리에 등록 -> 불필요한 파일은 미등록(.gitignore에서 관리)
  1) 파일 등록 (add)
  2) 수정된 상태 (status)
  3) 수정된 상태 다시 등록 (add)
  4) 상태 저장 (commit) - 내 로컬에만 저장되는 상태
  5) 상태 업로드 (push) - 현재 최종 커밋 상태를 remote 서버에 업로드

# 파일 서버에서 가져오기 (pull)
- git pull  
- git fetch
  
# 참고
- Windows 환겨에서 git 명령 문자열은 꼭 쌍따옴표(" ")를 사용해야 함  
- Linux의 경우 숨김파일(.)은 git add * 대상에서 제외될 수 있으니 주의  
- 커밋 시점 확인 (Version Control -> Log 탭)  
  - 태그는 최종 상태를 의미함
  - head 태그: 현재 보고 있는 프로젝트

# 단축키
- WebStorm에서 add + commit 한번에 수행 (코드 편집 창에서 Ctrl + K)

# 브랜치
- 브랜치 확인 git branch
- 브랜치 추가 git branch branch_name
- 브랜치 전환 git checkout branch_name 
- 브랜치에서 수정사항을 마스터에 병합 git merge branch_name -> 수행한 결과는 커밋한 것과 같음

# 원격 서버에 올리기
- 최초 등록 git remote add origin <원격 저장소 URL>  
- 올리기 git push origin master