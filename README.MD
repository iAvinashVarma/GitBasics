# GitBasics

Git Basics is continuation of Git Fundamentals by [Microsoft Visual Studio](https://youtu.be/c3482qAzZLQ).

## Instructions

Work with same local repository of Git Fundamentals.

```console
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

* Use Termux

```
pkg install git
```

### Save git credentials

```
git config credential.helper store
```
