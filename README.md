# Introduction

This is where I take notes for git commands.

# Commands

## Create git folder
- `git init` : create
or
- `git init .` : create


## Set up remote server
```
gh repo create 'name' --public
git remote add origin https://github.com/geepum/'name'.git
git branch -M main
git push -u origin main
```

## Branches
- `git branch` : list branches
- `git branch 'name'` : create branch
- `git checkout 'branch name'` : go to branch
- `git checkout -b 'branch name'` : create and go to branch

## Git log
- `git log` : see history of git commit
- `git log --branches` : see history of all branchs' git commits

## Merge
- `git checkout main` : go to main branch first
- `git merge 'branch name'` : then merge sub-branch to the main branch
- `git branch -d 'branch name'` : lastly, delete the merged branch
- 'git branch -D 'branch name'` : to delete UNMERGED branch
