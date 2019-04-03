# GitBasics

Git Basics is continuation of Git Fundamentals by [Microsoft Visual Studio](https://youtu.be/c3482qAzZLQ).

## Instructions

Work with same local repository of Git Fundamentals.

```cmd
git remote remove origin
git remote add origin https://github.com/iAvinashVarma/GitBasics.git
git remote -v
git rm LICENSE
git rm --cached README.md
git pull origin master --allow-unrelated-histories 
git add .
git commit -m "Updating README.MD."
git push origin master
```

## Mobile Instructions

* Use [Termux](https://play.google.com/store/apps/details?id=com.termux)

```bash
$ pkg install git
```

### Save git credentials

```cmd
<<<<<<< HEAD
$ git config credential.helper store
```

## Git History

```bash
$ git blame README.MD
$ git log --oneline --graph --decorate --abbrev-commit
```

### Access mobile storage

```bash
$ termux-setup-storage
=======
git config credential.helper store
>>>>>>> adc8805... Add log related commands.
```

## Git History

```cmd
git blame README.MD
git log --oneline --graph --decorate --abbrev-commit
```

### Access mobile storage

```bash
$ termux-setup-storage
```
