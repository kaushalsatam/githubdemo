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
