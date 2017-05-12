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

### 

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

## References

- [Bash Prompt PS](https://www.cyberciti.biz/tips/howto-linux-unix-bash-shell-setup-prompt.html)