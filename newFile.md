git init 초기화 돼서 .git 디렉토리가 생성됨
git add 통해서 필요한 파일을 git 관리에 등록 -> 불필요한 파일은 미등록(.gitignore에서 관리)
  1) 파일 등록 (add)
  2) 수정된 상태 (modified status)
  3) 수정된 상태 다시 등록 (add)
  4) 상태 저장 (commit) - 내 로컬에만 저장되는 상태
  5) 상태 업로드 (push) - 현재 최종 커밋 상태를 remote 서버에 업로드
  
  참고)
  Windows 환겨에서 git 명령 문자열은 꼭 쌍따옴표(" ")를 사용해야 함
  Linux의 경우 숨김파일(.)은 git add * 대상에서 제외될 수 있으니 주의
   