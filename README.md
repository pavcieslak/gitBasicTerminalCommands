# GitHub - Introduction
## Basic config
Before doing anything, make sure you add your name and email address to Git. That's how you do it.

-**git config** --global user.name "your name here"
-**git config** --global user.email "your email here"

## GitHub basic commands
-**git init** // initialize Local Git Repository
-**git --version** // check version of your Git
-**git add <file>** // Add selected file to the staging area
-**git add .** // Add all files to the index
-**git add *.html** // add any html file to stagind area
-**git rm --cached <file>**// removes the file from staging area
-**git status** // Check status of working tree (staging area)
-**git commit** // Commit changes in index

Here you have to press I to be able to actually write something. To exit this editor, simply write :wq and press Enter.

-**git commit -m** // Commit changes in index and add a message
-**git push** // Push to remote repository
-**git pull** // Pull latest from remote repository
-**git clone** // Clone repository into a new directory (current folder)

## Additional usefull terminal comands
-**touch <index.html>** // touch command creates files, in this case index.html
-**touch .gitignore** // here we can specify which files we want git to ignore whilst adding to the staging area or commiting to our tree

Inside .gitignore you simply add the files you want git to ignore by typing them like inline, one by one like this:

-log.txt ignore log.txt file
-/temp ignore entire temp folder
-*.txt ignore all text files

## Branches
-**git branch <login>** // creates a branch called login
-**git checkout login** // open previously created login branch
-**git merge login** // once done working on this branch and everything is working, merge your login branch to your master branch. The important thing here is that try to switch into your target branch first and then use merge to move changes into it.
-**git branch -m <app01> <newName>** // this is how you can rename your branches. In this instance, we are renaming app01 to newName.
-**git branch -d <branch name>** // to delete a branch use -d.
-**git branch -D <branch name>** // same as above with the difference that it's like force delete.