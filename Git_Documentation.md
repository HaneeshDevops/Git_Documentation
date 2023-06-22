# Git_Documentation

## This command initializes a new Git repository in the current directory. It sets up the necessary Git data structures and creates a hidden .git folder where Git will store its files and metadata
```sh
git init
```
## after init you need to add some files to persist the master branch. if dont add any files and add ,commit it won't save the changes.
```
touch README.md
```
## add the above changes into staging area & move to commited files
```
git  add . ; git commit -m "README.md"

```
## Now check the available branches
```
git branch
```

## now create a remote repository & connect local repo with remote repo.
```
git remote add <url>
```
## That's it now you can modify the files locally & after dont forget to add & commit the changes . you can start pushing & pulling

## git command to add local branch to remote repo
```
git push --set-upstream origin master2
```
## git command to Fetch and merge changes from a remote repo to  local branch 
```
git pull origin master
```
 ## Git command to Lists all branches in the repository.
 ```
git branch
```
## Git command to create branch name in the repository
```
git branch <branch_name>
```
##  Git command to Switch to the specified branch.
```
git checkout <branch_name>
```
##  Git command to create branch and switch to the specified branch at a time
```
git checkout -b <branch_name>
```
##  Git command to Combine the specified branch into the current branch.
```
git merge <branch_name>
```
##  Git command to delete branch
```
git branch -d <branch_name>
```
##  Git command to Show the status of your working directory and staging area.& don't forget to check status after changes done 
```
git status
```
##  Git command that allows you to temporarily save changes that are not ready to be committed, allowing you to switch branches or perform other operations without committing incomplete work.
```
git stash

```
##  Git command to creates a new commit that undoes the changes made in the specified commit. It allows you to safely undo a commit without discarding any history.
```
git revert <commit>
```
##  Git command that allows you to reset your current branch to a specific commit. 
```
git reset <commit>
```
##  Git command that downloads the latest changes from the remote repository without merging them into your local branches. It updates your remote-tracking branches.
```
git fetch
```
##  Git command to displays the commit history in reverse chronological order, showing the commit hash, author, date, and commit message for each commit.
```
git log
```
##  Git command to Applying specific bug fixes , Reapplying changes after branch rebase , Extracting specific commits from one branch to another
```
git cherry-pick
```

