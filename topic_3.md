[Back To Topic List](README.md)

# Git commands and terminology:

## Merge
Merging  is Git's way of putting together a united history again. The git merge command allows you to take independent lines of development made by a git branch and merge it into a single branch.	

Example:- 
We have a new branch feature that is based off the master branch. We now want to merge this feature branch into master.

![](Images/img1.png)

Using this command we have a new branch feature that is based off the master branch. We now want to merge this feature branch into master.

![](Images/IMG2.png)

## Checkout

The git checkout command lets you navigate between the branches created by git branch. 

```	
 git checkout -b <branchname>  

git checkout -b <branchname>  

git checkout <remotebranch> origin/<remotebranch> 
```

## Push

The git push command allows you to send the commits from your local branch in your local Git repository to the remote repository.

Before you push from local to the remote repository, you must make sure that all the changes are committed on the local repository.

```
 git push <repo name> <branch name>
```
![](Images/PUSH.PNG)
