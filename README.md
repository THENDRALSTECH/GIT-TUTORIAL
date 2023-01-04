# GIT-TUTORIAL

##GIT
```Free and open source version control system```

##GIT COMMANDS

```->Clone-bring the repo that is hosted on github into a folder on your local machine.
->add-Track your files and changes in git commit-save your files in Git.
->push-upload git commits to a remote repo.
->pull-download changes from remote repo to your local machine.
->Commit-Save your files in git
->status```

```-->DIRECTORY: Folder
-->TERMINAL OR COMMAND LINE: Interface for text commands
-->CLI: Command Line Interface
-->cd: Change directory
-->CODE EDITOR: Word processor for writing code.
-->Repository: Project, or the folder/place where your project is kept.
-->GITHUB: A website to host your repositories online.
-->GIT: tool that tracks the changes in your code overtime```

##Installing GIT for windows

```![image](https://user-images.githubusercontent.com/121928201/210593660-b0630c76-81fe-498a-bb17-e9b141cead59.png)
![image](https://user-images.githubusercontent.com/121928201/210593871-4ea23800-912b-419a-8f0f-2a74ab98d445.png)
Generting key
![image](https://user-images.githubusercontent.com/121928201/210593919-27f7de03-88cf-4064-b07e-425de78b2147.png)```
###-> paste it in the ssh key and adding the repository.


## CLONE
###STEPS

```1) Git cloning
       git clone (link http or ssh)
   2) To display the everything
         ls-la
   3) To view the status of the repo
        git status
   4) To track files
       git add (filename including extension)
       Track all changes
       git add .
   5) To add a message and description
        git commit -m (filename) -m (description)```
      
# STEPS FOR PUSH AND PULL

## 1) To generate keys
     ssh-keygen

## 2) Push command
     git push origin master

## To create a folder locally

     git init
     git status
     git add
     git commit

## Create an empty repository in github
      git remote add origin(link of the empty repo)

## To display the activity
       git remote -v
       
## Upstreaming
     git push -u origin master/main

# GIT_BRANCHING

1)Master branch-default branch
 * Creating the clone of master branch as "feature branch".

2)Feature branch-additional branch
 * When we make changes in the master branch it does affect the feature branch similarly for master branch.

 3)Hotfix branch-bug fixing branch

# Steps for branching

## 1)  Command to indicate current branch 
        git branch
     
## 2)  Checkout used to switch between branches 
       it checkout -b branchname 
  
## 3)  Add to git repo
       git add
       git commit -m (filename) -m (description)
       git push origin master
## 4) Combing the step of adding and committing
       git commit -am
       
       
# MERGING BRANCHES

## To find the difference between branches
     git diff branchname
## To find the status of the file
     git status
## Push the changes into the repo
     git -u origin branchname
     
# STEPS TO DELETE A FEATURE BRANCH AFTER MERGING
      git branch
      git branch -d branchname
 
 # STEPS TO UNDO A GIT 
       git reset filename(to remove commit)
       git reset HEAD ~1
 ###### head is a pointer to last commit.
 
 
 # TO FIND ALL THE COMMITS IN CHRONOLOGICAL ORDER
       git log
       

# FORKING
* Complete copy of the repository
* It is used to make changes in the file when the user do not have the access to edit.
       
