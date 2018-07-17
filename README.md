# GitBasics
Git Basics is continuation of Git Fundamentals by [Microsoft Visual Studio](https://youtu.be/c3482qAzZLQ).

## Instructions

```console
git init
echo '# Git Fundamentals' >> README.MD
git status
git add README.MD
git commit -m "Initial README file."
git log
git log --oneline
echo '.git/*' >> .gitignore
git add .gitignore
git commit -m "Adding gitignore file."
git remote add origin https://github.com/iAvinashVarma/GitFundamentals.git
git remote -v
git push -u origin master
```

Update the README.MD from GitHub Web.

```console
git fetch origin master
git merge origin/master
```

Or

```console
git pull origin master
```
