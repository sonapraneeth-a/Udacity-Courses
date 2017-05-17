# Notes

## Lesson 1: Navigating a Commit History

### 1.4: Finding Diffs Between Larger Files

```bash
$ diff -u game_old.js game_new.js
```

### 1.12: Using Git to view history

```bash
$ git log
$ git diff
$ git commit -m<message>
```

### 1.17: Git Commits Across Multiple Files

```bash
$ git log --stat
$ git diff <commit-id-1> <commit-id-2>
```

### 1.21: Cloning and Exploring The Repo

```bash
$ git clone <repo-url>
$ git config --global color.ui auto
```

### 1.25: Checking Out Old Versions of Code

```bash
$ git checkout <commit-id>
```

### 1.3x: 

```bash
$ git config --global core.editor "subl -n -w"
$ git config --global push.default upstream
$ git config --global merge.conflictstyle diff3
```

### Summary

| Command | Description |
|---------|-------------|
| git log |  |
| git diff |  |
| git commit -m<message> |  |
| git config --global color.ui auto | Get colored diff output |
| HEAD | Commit you're currently working on |
| git checkout |  |

## Lesson 3: Creating and Modifying a Repository

### 3.3: Initializing a Repository

```bash
$ git init
```

### 3.4: Examining the New Repository

```bash
$ git status
```

### 3.6: Staging Area

```bash
$ git add <file-names>
```

### 3.11: git diff Revisited

```bash
$ git diff
$ git diff --staged
$ git reset --hard
```

### 3.12: Commit the Bug Fix

```bash
$ git checkout master
```

### 3.14: Branching

```bash
$ git branch
$ git branch <branch-name>
$ git checkout <branch-name>
```

### 3.18: Branches for Collaboration

```bash
$ git log --graph --oneline <branch-names>
```

### Detached HEAD Revisited

```bash
$ git checkout -b <branch-name>
```

### 3.25: Merging on the Command Line

```bash
$ git merge <main-branch> <sub-branch>
$ git merge <sub-branch>
$ git show <commit-no>
$ git merge --abort
```

### 3.31: Committing the Conflict Resolution

```bash
$ git log -n 1
```

### Summary

| Command | Description |
|---------|-------------|
| git init | Initialize a git repository |
| git status | Get the status of git repository |
| git diff |  |
| git diff --staged |  |
| git reset --hard |  |
| git branch |  |
| git checkout master |  |


## Lesson 4: Using Github to collaborate

### 4.5: Adding a remote

```bash
$ git remote
$ git remote add origin
$ git remote -v
$ git push origin master
```


## References

- [Bash Prompt PS](https://www.cyberciti.biz/tips/howto-linux-unix-bash-shell-setup-prompt.html)