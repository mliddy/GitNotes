###	[Github basics](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV)
* Github pages probably not needed. 
* Gitbash (needed for windows) 

###	Adding SSH
* https://www.youtube.com/watch?v=H5qNpRGB7Qw 
* https://help.github.com/en/enterprise/2.15/user/articles/adding-a-new-ssh-key-to-your-github-account
###	Git status 
###	Git reset –soft HEAD~1
* https://git-scm.com/docs/git-reset
* Will prob need to force ( add –force) pushes to remote branches after doing this command locally
* Git push –force <remote > <local branch>:<remote branch>
###	Git commit -am”commit message”
###	Git push **remote localBranch:remoteBranch** 
* Will create remote branch if not exist. 
###	Git rebase 
* Git rebase master
* Git rebase <remote> <branch> 
###	Branches
* Git checkout -b [NewBranchName] 
* Git checkout -d [BranchName to be deleted] 
* Git branch 
* Git checkout [branch]
###	Git stash 
* Git stash (need to add everything first[  git add . ] 
* Git stash apply
###	Git log 
###	Git cherry-pick <branch id> 
