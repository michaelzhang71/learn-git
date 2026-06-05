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

> after git init, a subdirectory `.git` will be created where all git infomation is stored

> working area: where you work on code
> staging area: where you prepare your changes for a commit
> commit area: a snapshot of your project at a specific point in time

## 3. Add Files to the Staging Area

```shell
git add filename.ext // add a single file to the staging area

git add . // add all files in the working area to the staging area

git add -A // add all files in the working area to the staging area, including deleted files
```
