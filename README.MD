# Cheat Sheet for Git/Github
## Hello Friends, I Mrudul Chaudhari, made this repo to practice and share what I learnt on git in the past few days. Main intention is to refer some while I am learning and practicing and to increase my knowledge in the field.
##  Clone & Status
### >>>git clone <some-link> - used to copy repo in the local machine
### >>>git status - will return the status, i.e. if the files in the git are tracked and the modified data in them is pushed.
## Add & Commit
### >>>git add <file-name> - adds new file or changed files in your working directory to the Git Staging area
### >>>git commit -m "Some message" - it is the record of change
## Push
### >>>git push origin main - upload local repo content to main remote repo

## to create a new repo
### >>>mkdir <repo name>
### >>>git init
### >>>git remode add origin <link> - the new repo has to be made on github as well and the link to be added in <link>
### >>>git remote -v - to verify remote

## Branch
### >>>git branch - to get the current branch working on
### >>>git branch -M <new name> - to rename branch
### >>>git checkout <branchname> - to navigate through branches
### >>>git checkout -b <branchname> - to create a new branch
### >>>git branch -d <branchname> - to delete a branch

## To merge two contents of diff brancehs
### Way 1
### >>>git diff <branch name> - used to check the diff bw the current branch and the branch name mentioned
### >>> git merge <branch name> - used to merge two content
### Way 2
### creating a pull request, this will happen on github
### To see changes happened on github, the local pc has to give a pull command
### >>>git pull main origin

## Undoing Changes
### Staged change -> change that has been added but not commited. This will not bring back the content, but remove from the added seciton
### >>>git reset <filename> - for a particular file name
### >>>git reset - for multiple files

### For committed change (for one commit)
### >>>git reset HEAD~1 -> by default the latest commit is known as HEAD~1

### >>>git log -> shows all past commits

### Committed changes (multiple)
### >>>git reset <commit hash> -> every commit has a hash, that needs to be added
### >>>git reset --hard <commit hash> -> This will bring back the old code on vs code

## FORK
### new repo that shares code - it is a rough copy




