Setup & Config
==============
git init - to initialize the git tracking
git config --global user.name shashank - configure username
git config --global user.email xyz@gmail.com - configure email

Basic Workflow
==============
git add shashank.txt - to add shashank.txt in staging area
git commit -m "shashank.txt is added" - shashank.txt is now under git tracking with a message
git push origin main - push file from local to remote
git pull origin main - update the already existing repo's by latest commit

Viewing Changes
===============
git status  - check the status on which state file is
git log - check the log of file, branch info etc

Adding additional
================
git checkout -b dev = move to new branch name dev
git checkout master = return to master
git branch = see the branches list
git git branch -D dev = delete the dev branch

git clone url = clone the complete repo to our local
git remote -v = check where is remote repo is located in our local


