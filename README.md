# mygitcommands
This repository is used to record all the useful git commands I've been using 

## 1. Config 

Add a new remote

`git remote add origin git@github.com:User/UserRepo.git`

Change the url of an existing remote repository

`git remote set-url origin git@github.com:User/UserRepo.git`

Show config

`git config --list`

## 2. Log

To show commit history 

`git log`

`git log --oneline`

To show changes in a specific commit

`git show commit_id`

`git show commit_id --name-only`

## 3. Add

Undo add file

`git reset <file>`

Undo add all

`git reset`

## 4. Commit 

Undo commit and add to all

`git reset HEAD~`

## 5. Branch

Delete local branch

`git branch -d <branch_name>`

Delete remote branch

`git push -d <remote_name> <branch_name>`

