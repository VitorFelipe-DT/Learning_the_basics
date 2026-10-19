# Learning the basics

Project to practice Git and GitHub

## Git commands used

###Creating the first commits
```bash
git add .
git commit - "Step one"
```


### Creating a branch with checkout
```bash 
git checkout -b igor-branch
git add README.md
git commit -m "Add other way to change the branch and enforce a conflict"
```

###Merging and connecting to GitHub
```bash
git switch main
git merge my-first-branch
git remote add origin https://github.com/VitorFelipe-DT/Learning_the_basics
```

###Pushing to GitHub
```bash
git push -u origin main 
git push -u origin my-first-branch
```

###Creating the README and amending the commit message 
```bash
git switch my-first-branch
git add README.md
git commit -m "add readme"
git commit --amend -m "Add README with project description"
git push
```
###Pull Request
Opened on GitHub: base 'main' <- compare 'my-first-branch'
