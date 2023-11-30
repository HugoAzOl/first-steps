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

  # rename a branch
  git branch -M main
  git remote add origin https://github.com/HugoAzOl/first-steps.git
  git push -u origin main
```