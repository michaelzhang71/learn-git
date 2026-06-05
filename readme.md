# Git 学习

## 1. Git configaration

```shell
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
git config --global init.defaultBranch main
```

## 2. Initialize a New Repository

```shell
cd my-new-project
git init

or

git init my-new-project
cd my-new-project
```

> 1. after git init, a subdirectory `.git` will be created where all git infomation is stored

> 2. working area: where you work on code
> 3. staging area: where you prepare your changes for a commit
> 4. commit area: a snapshot of your project at a specific point in time

> 5. best practice: create a .gitignore file to ignore files you don't want to track in git before you start working

## 3. Add Files to the Staging Area

```shell
git add filename.ext // add a single file to the staging area

git add . // add all files in the working area to the staging area

git add -A // add all files in the working area to the staging area, including deleted files

git status // check the status of the working area and the staging area

git commit -m "commit message" // create a new commit with the changes in the staging area

git log // check the commit history
git reflog // check the ref history, including all branches and tags created
```
