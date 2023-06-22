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
## git command to add remote repo to  local branch 
```
git pull origin master
```
