# ***Git Cheat Sheet***
# The most basic and essential commands.
## Installation
After you have [downloaded](https://git-scm.com/) git from the URL you can continue with the content below.

#
## Setup 
### ``` git config --global user.email "yourEmail"```
-  This commands let's you set up a email id that will be displayed in your commits
### ```git config --global user.name "yourName"```
- This commands let's you set up a name that will be displayed in your commits
  
##  Initialization
### ```git init```
- This initializes a new git repo locally in your project root
- Follow the commands below to start using version control software
  
### ``` git add filename.filetype```
- Adds the mentioned file to the staging area
- Just replace the filename.filetype to your file name
- To add everthing in your repo just use ``` git add .```

### ``` git status```
- To show the current status of your repository 
- The status includes staged,unstaged and untracked files.
  
### ``` git commit```
- This will open up an editor to add the commit message to the changes done in the repositories.
- If you don't want a editor to open up everytime you make a commit use the command ```git commit -m "your message"```
  
### ``` git log```
- This will show the commit history for the repo along with the commit id for each commit.
- you may even use ```git log -p``` to view the commit history along with the all the files and their changes. 
  
#
## How to ignore files in git

- Create a ```.gitignore``` file and commit it
- Add all the files that you want to ignore in your git repo inside the ```.gitignore``` file

#
## Roll back to a older or a specific version

### ``` git revert commit_ID```
  
#

## Branches in git

### ``` git branch branchName```
- By default you will be in the main branch. With this command you can create new branch 
- Git wont automatically switch to any branch you should change branch with the next command
  
### ``` git checkout branchName```
- Used to switch to a specific branch
- To get a list of existing branches use the command ```git branch```

#

## How to add and work on a remote repository in Git

### ```git add remote https://repo_here```
- Adds a remote repository to your local repository(from gitHub, gitlab or any other cloud based git hosting domains).
  
### ``` git push```
- After you are done working your local repository you can push the changes into your remote repository using the above command.
  
    






  


  



  

