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