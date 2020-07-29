# GIT COMMANDS

## Check if git is installed

`git --version`

## Log  in  ( identify yourself )

* Set the user name
  
  `git config --global user.name "your name here"`

* Set the user email

  `git config --global user.email example@email.com`

* Show current username and email

   `git config --list`

## Start a local repository

 At the command line ( terminal ) and inside the project folder, type:

   ` git init`

- Obs :
 
   To DELETE a repository:

   ` rm -rf .git`

   This command will delete the .git folder that was inside of your project folder.

   rm = delete file

   -rf = force recursive deletion (because is a folder)

## Check the status of git

To see which files have been changed:

`git status`

## Add file to be tracked

`git add example.txt`

Add all the files created in your folder to be tracked:

`git add .`

## Commit

`git commit -m "Type a message here about what has changed"`


## View the history of commits

 `git log`

 ---

 ## Push a repository to GitHub
After creating a new repository on your github page, copy the URL of your repository and insert it at the end of this command:

` git remote add origin <adress repository>`

 And after:
 
 `git push -u origin master`

After the first push on the master branch, the next commits you can push as follows:

 `git push`

 



