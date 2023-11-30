# first-steps
## html first-steps
```
<html></html>
```

## git first steps
```
#  Indentity settings on git

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

# checking identity on git
  git config --get user.email
  git config --get user.name

# Initialzing a new repository
echo "# first-steps" >> README.md
  git init
# staging files to commit
  git add README.md
# checking staged files
  git status
# writing a commit
  git commit -m "first commit"
# checking previous commits on current branch
  git log
# rename a branch
  git branch -M main
# checking all available branches and which is the current branch
  git branch -a
# adding to a remote repository
  git remote add origin https://github.com/HugoAzOl/first-steps.git
# pushing changes to a remote branch
  git push -u origin main
```