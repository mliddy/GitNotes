## Tips
* **Open repo in VsCode and look at source control tab before and after executing each of these commands**
  * To open from terminal/cmd cd to repo and run **code .** or use VsCode gui. 
* **run git status & git log before & after each command to see changes**

###	[Github basics](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV)
* Github pages probably not needed. 
* Gitbash (needed for windows) 

###	[Git remote ](https://help.github.com/en/github/using-git/adding-a-remote) 
* **Add remote:** git remote add **remoteName link**
* **List of remotes with URLS:** git remote -v 

###	Adding SSH
* https://www.youtube.com/watch?v=H5qNpRGB7Qw 
* https://help.github.com/en/enterprise/2.15/user/articles/adding-a-new-ssh-key-to-your-github-account

###	Git status 

###	Git commit -m”commit message”
Commits staged changes, with a commit message. 

###	Git reset --soft HEAD~1
* https://git-scm.com/docs/git-reset
* Will prob need to force ( add –force) pushes to remote branches after doing this command locally
  * Git push –force (remote ) (local branch):(remote branch)
  
  
###	Git push **remote localBranch1:remoteBranch1** 
* Pushes changes on _localBranch1_ to _remoteBranch1_. Creates _remoteBranch1_ if it doesn't exist. (names don't need to match) 

###	Git rebase 
* Update from local master: Git rebase master
* Update from remote master: Git rebase [remote] [branch] 
rebase is very useful when solving mrege conflicts, it updates your branch and applys your commits ontop. 


###	Branches
* Create a new branch and change to it: git checkout -b [NewBranchName] 
* Delete a local brach:  git checkout -d [BranchName to be deleted] 
* list of local branches: git branch 
* Change branch: git checkout [branch]
* Delete Remote branch: git push --delete (remote) (branchName) 

###	Git stash 
* Git stash (need to add everything first[  git add . ] 
* Git stash apply
###	Git log 
###	Git cherry-pick [Commit -id] 
use cherry pick to copy commits from one brannch to another. You can get the _commitId_ using **git log**. 

### [MarkDown CheetSheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

###How to Update your forked master, where origin points to main master. 
* change to master branch
* git pull 
* git push (ForkRemote) master
