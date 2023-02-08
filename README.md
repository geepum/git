# Introduction

This is where I take notes for git commands.

# Commands

- Create git folder
```
git init
or
`git init .
```

- Set up remote server
```
gh repo create 'name' --public
git remote add origin https://github.com/geepum/'name'.git
git branch -M main
git push -u origin main
```

- Branches
```
git branch <!--- list branches --->
git branch 'name' ###create branch
git checkout 'branch name' ###go to branch
git checkout -b 'branch name' ###create and go to branch
```

- Git log
```
git log ###see history of git commit
git log --branches ###see history of all branchs' git commits
```
