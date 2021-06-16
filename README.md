# Learn Git

## Basic git interaction
  * Do changes
  * Add files to staging area
  * Commit changes


## Git commands cheat sheet

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