# Git Hook Sample. 

pre-commit, commit-msg 두 종류의 hook에 대한 sample. 

## 파일 설명. 
* .githooks/pre-commit : pre-commit hook. 
  특정 파일을 커밋하지 못하도록 하는 hook. sample에서는 환경 변수를 담을 .env 파일과 pre-commit, commit-msg hook 파일을 commit하지 못하도록 함. 
* .githooks/commit-msg 
  commit 메시지에 ISSUE 번호를 넣지 않으면 commit 되지 않도록 함. 
## 설정 방법. 
```bash
git clone https://github.com/ikaruce/githooks.git
cd githook
git config core.hookspath .githooks
```



## 관련 글. 

https://medium.com/@ikaruce/git-%EB%82%98%EC%81%9C-commit%EC%9D%84-%EB%A7%89%EA%B8%B0-10a906bc8352
