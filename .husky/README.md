# 커밋 워크플로 훅	
pre-commit :	commit 을 실행하기 전에 실행
prepare-commit-msg :	commit 메시지를 생성하고 편집기를 실행하기 전에 실행
commit-msg :	commit 메시지를 완성한 후 commit 을 최종 완료하기 전에 실행
post-commit :	commit 을 완료한 후 실행
# 이메일 워크플로 훅	
applypatch-msg :	git am 명령 실행 시 가장 먼저 실행
pre-applypatch :	patch 적용 후 실행하며, patch 를 중단시킬 수 있음
post-applypatch :	git am 명령에서 마지막으로 실행하며, patch 를 중단시킬 수 없음
# 기타 훅	
pre-rebase :	Rebase 하기 전에 실행
post-rewrite :	git commit –amend, git rebase 와 같이 커밋을 변경하는 명령을 실행한 후 실행
post-merge :	Merge 가 끝나고 나서 실행
pre-push :	git push 명령 실행 시 동작하며 리모트 정보를 업데이트 하고 난 후 리모트로 데이터를 전송하기 전에 실행. push 를 중단시킬 수 있음