# Learn Git

## Basic git interaction
  * Do changes
  * Add files to staging area
  * Commit changes


## Git commands cheat sheet

## Local repository
### 1. Init empty git repository
```
$ git init
```

### 2. Add files to Staging Area
```
$ git add [filename]
```
to add all files
```
$ git add .
```
to add files with particular format
```
$ git add *.exe
```

### 3. Check the changes in staging area
```
$ git status
```
short status command
```
$ git status -s
```

### 4. Commit the changes
```
$ git commit -m 'commit message'
```

### 5. Commit file and add to stating simultaneously
```
$ git commit -a -m 'commit message'
```

### 6. Remove file from staging area
```
$ git rm --cached filename
```

### 7. Get the commit history (log)
```
$ git log
```

### 8. Amend the last commit message
```
$ git commit --amend
```

### 9. Add the forgotten change with the last commit message
```
$ git commit --amend --no-edit
```

### 10. Unstage files to add stage again with different commit
```
$ git restore --staged filename
```


## Remote repository

Create the repository on any repository hosting platform like Github, Gitlab or Bitbucked and add local to remote. or clone remote repository.

### 11. To check local repository is connected to which remote repository or not.
```
$ git remote -v
```

### 12. Add local repository to remote repository
```
$ git remote add origin 'url'
```

### 12. Connect local master branch to remote master branch
```
$ git branch -M main
$ git push -u origin main
```