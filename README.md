# githubdemo

This is my first Github repository.<br>
Author - Kaushal Satam

Some git commands:

<!-- cloning github repository/project -->

git clone <-url->

<!-- version -->

git --version

<!-- change directory to child folder -->

cd <-childfoldername->

<!-- change directory to parent folder -->

cd ..

<!-- create new folder -->

mkdir <-foldername->

<!-- list contents of the folder -->

ls

<!-- list contents of the folder including hidden files -->

ls -a

<!-- displays status of code -->

git status

modified / untracked -> add -> staged -> commit -> unchanged

<!-- add files / save changed files -->

git add <-filename->

<!-- to save multiple changes -->

git add .

<!-- commit -->

git commit -m "commit change message"

<!-- finally upload local repo content to remote repo -->

git push origin main

<!-- set upstream if you want to save your progress on same project/repo-->

git push -u origin main

<!-- next time you dont have type whole command, just type -->

git push

<!-- create new git repo -->

git init

<!-- command to run before pushing the repository on github to set remote repository -->
<!-- but firstly you have to create dummy repository on github to get the link and link
    the remote and local repositories together -->

git remote add origin <-link->

<!-- to check the remote repo -->

git remote -v

<!-- to check the current branch -->

git branch

<!-- to rename a branch -->

git branch -M <-newname->

<!-- new branch -->

git checkout -b <-branchname->

<!-- delete branch -->

git checkout -d <-branchname->

<!-- change branch -->

git checkout <-branchname->

<!-- merge branch -->
<!-- Way1 -->
<!-- to compare commits, branches, files & more -->

git diff <-branchname->

<!-- merge -->

git merge branch

<!-- Way 2 -->

<!-- by GitHub
Create a pull request.
Pull Request: It lets you tell others about changes you've pushed to a branch in a repository on GitHub. -->

<!-- pull command: used to fetch and download content from a remote repo and immediately update the local repo to match that content -->

git pull origin main

<!-- Resolving merge confict -->
<!-- An event that takes place when Git is unable to automatically resolve differences in code between two commits -->

<!-- undoing changes -->
<!-- case1: staged changes -->

git reset <-filename->
git reset

<!-- case2: commited changes(for one commit) -->

git reset HEAD~1

<!-- case3: commited changes(for many commits) -->
<!-- hash is unique value given to a particular commit -->

git reset <-commithash->
git reset --hard <-commithash->

<!-- to see older commit changes -->

git log

<!-- fork -->
<!-- A fork is a new repository that shares code and visibility settings with the original "upstream" -->
<!-- fork is a rough copy of a repository -->

<!-- You can use fork to copy others project make changes and then create pull request to merge changes with original project/repo-->
