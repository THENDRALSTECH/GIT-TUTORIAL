# GIT-TUTORIAL

## GIT
```Free and open source version control system```

## GIT COMMANDS

```->Clone-bring the repo that is hosted on github into a folder on your local machine.
   ->add-Track your files and changes in git commit-save your files in Git.
   ->push-upload git commits to a remote repo.
   ->pull-download changes from remote repo to your local machine.
   ->Commit-Save your files in git
   ->status
```

## BASIC TERMS

```-->DIRECTORY: Folder
   -->TERMINAL OR COMMAND LINE: Interface for text commands
   -->CLI: Command Line Interface
   -->cd: Change directory
   -->CODE EDITOR: Word processor for writing code.
   -->Repository: Project, or the folder/place where your project is kept.
   -->GITHUB: A website to host your repositories online.
   -->GIT: tool that tracks the changes in your code overtime
```

## Installing GIT for windows

```![image](https://user-images.githubusercontent.com/121928201/210593660-b0630c76-81fe-498a-bb17-e9b141cead59.png)
![image](https://user-images.githubusercontent.com/121928201/210593871-4ea23800-912b-419a-8f0f-2a74ab98d445.png)
Generting key
![image](https://user-images.githubusercontent.com/121928201/210593919-27f7de03-88cf-4064-b07e-425de78b2147.png)
```
##-> paste it in the ssh key and adding the repository.


## CLONE
### STEPS

```--> Git cloning
       git clone (link http or ssh)
   --> To display the everything
         ls-la
   --> To view the status of the repo
        git status
   --> To track files
       git add (filename including extension)
       Track all changes
       git add
   --> To add a message and description
        git commit -m (filename) -m (description)
```
      
      
## PUSH AND PULL
  ``` --> To generate keys
        ssh-keygen
      --> Push command
        git push origin master
```
## For creating a local folder

```git init
     git status
     git add
     git commit
```

### Create an empty repository in github
      git remote add origin(link of the empty repo)
     

### For activity or status displaying
       git remote -v
       
       
### For  Upstreaming
     git push -u origin master/main

## GIT_BRANCHING

```-->Master branch-default branch
  Creating the clone of master branch as "feature branch".

-->Feature branch-additional branch
  When we make changes in the master branch it does affect the feature branch similarly for master branch.

 -->Hotfix branch-bug fixing branch
```
###  BRANCHING
#### STEPS

## -->  Command to indicate current branch 
        git branch
     
## -->  Checkout used to switch between branches 
       it checkout -b branchname 
  
## -->  Add to git repo
       git add
       git commit -m (filename) -m (description)
       git push origin master
## --> Combing the step of adding and committing
       git commit -am
       
       
## MERGING BRANCHES

### Difference between branches
     git diff branchname
### Status of the file
     git status
### Push the changes into the repo
     git -u origin branchname
     
## DELETE A FEATURE BRANCH AFTER MERGING
### STEPS

      git branch
      git branch -d branchname
 
## TO UNDO A GIT
### STEPS

       git reset filename(to remove commit)
       git reset HEAD ~1
 
 ##  CHRONOLOGICAL ORDER COMMITS
       git log
       

### FORKING
--> Complete copy of the repository
--> It is used to make changes in the file when the user do not have the access to edit.
       
