# git init 
- 현재 폴더를 git 폴더로 지정해서 버전 관리를 시작함
- .git 폴더가 만들어지면서 git에 의해 모니터링이 시작됨.


# git status  
- 현재 폴더의 git 상태를 보여줌.

# git add <file>

- Stage -> Working   :  git restore --staged <file>

# git commit -m "message" 

- Commited -> Working : git checkout -- <file>


# git config 

- git --global user.name "B.C.Lee"

- git --global user.email "bcleemd@gmail.com"

```
git config --global --edit
git commit --amend --reset-author  # amend : 개정하다, 수정하다. 
```


# .gitignore 파일..   버전관리에서 재외하기  

```
mynote.txt
temp/
.swp ( 확장자 지정)
```

