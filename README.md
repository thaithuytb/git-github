# Git, Github ( basic)

1. Git status
2. Git add .
3. Git commit -m

## details

### 1

- use git status (have red files) -> ***staying working diredtory***

- git add ***working directory -> statging area***
- git commit ***statging area -> git repository***
- git log to show all infomation about all commits

### 2

- git rm --cached <name.file> or git reset <name.file> ***stating area -> working dir***

- git reset -soft (**id of commit**) -> comeback about old commit and  all line code of commits laster will about stage
- git reset -hard (**id of commit**) -> comeback about old commit and  all line code of commits laster will be detele
- git reset -mixed (**id of commit**) -> comeback about old commit and  all line code of commits laster will about working
- use git reset --soft HEAD~N (N is number commit: ex: 1,2,..) then commit and push to github with ( git push origin ***name branch*** -f
