# PROJECT_1_22BEE0348
### An overview of git command : 
   
Git supports many command-line tools and graphical user interfaces. The Git command line is the only place where you can run all the Git commands.  
   
   
### 1. Git config command :   
  The git config command is a convenience function that is used to set Git configuration values on a global or local project level.  The Git config command is the first and necessary command used on the Git command line.  
`git config --global user.name " VIJAY_KUMAR_MEENA " `  
  
  git config --global user.email "vijaymeenavit@gmail.com"  
  

### 2. Git Init command :  
The git init command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository.   
`git init [Repositry name]`  

### 3. Git clone command :  
git clone is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location. The original repository can be located on the local filesystem or on remote machine accessible supported protocols. The git clone command copies an existing Git repository.  
  
  git clone https://github.com/vijaymeena1588/PROJECT_1_22BEE0348.git  
  

### 4. Git add command :  
 adds a change in the working directory to the staging area.  
 `git add Project 101`  
 
### 5. Git commit command :  
Commit command is used in two scenarios.  

#### Git commit-m
This command changes the head. It records or snapshots the file permanently in the version history with a message.  

` git commit -m " Commit Message"`  

#### Git commit-a  

This command commits any files added in the repository with git add and also commits any files you've changed since then.  

` git commit -a`  
### 6. Git status command :  
The git status command displays the state of the working directory and the staging area.   
` git status `

### 7. Git push command :  
used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo.  
` git push`  

### 8. Git pull command :  
Pull command is used to receive data from GitHub. It fetches and merges changes on the remote server to your working directory.  

` git pull [URL]`  

### 9. Git branch command :  
 lets you create, list, rename, and delete branches.  
` git branch`  
### 10. Git merge command :   
This command is used to merge the specified branch's history into the current branch.  
` git merge`  

### 11. Git log command :  
Git's basic tool for exploring a repository's history.  
`git log`  
### 12. Git remote command :  
lets you create, view, and delete connections to other repositories. Remote connections are more like bookmarks rather than direct links into other repositories.  
` git remote / fit remote add`  
### 13. Git fetch command :  
It downloads objects to the local machine without overwriting existing local code in the current branch.   
` git fatch`  
### 14. Git checkout command :  
lets you navigate between the branches created by git branch . Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.  
` git checkout [branch name]`  
### 15. Git diff command :  
Diffing is a function that takes two input data sets and outputs the changes between them. git diff is a multi-use Git command that when executed runs a diff function on Git data sources. These data sources can be commits, branches, files and more.  
` git diff`  
### 16. Git reset command :  
To review, git reset is a powerful command that is used to undo local changes to the state of a Git repo.  

` git reset`  
### 17. Git rm command :  
 used to remove individual files or a collection of files. The primary function of git rm is to remove tracked files from the Git index.  
  `git rm`  
 ### 18. Git stash command :   
 takes your uncommitted changes (both staged and unstaged), saves them away for later use, and then reverts them from your working copy.   
 `git stash`  
 ### 19. Git tag command :   
 ref's that point to specific points in Git history   
 `git tag`   
 ### 20. Git mv command :   
 move or rename a file, a directory, or a symlink.  
 `git mv`  
 
