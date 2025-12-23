# Git-branching 
This is the documentation that conatins the concepts of Leran Git Branching 
Learn GIt Branching 
Git branching allows you to create a separate line of development so you can work on new features or fix bugs without affecting the main code. It helps keep the main branch stable while changes are developed and tested independently. Once the work is complete, the branch can be merged back into the main branch.

Understand what a branch is –a separate line of work from the main code.
 About Git Commits 

A **commit** in Git is like saving a snapshot of your project at a specific point in time. It records the changes you made to files along with a short message explaining what was changed. Commits help track progress, go back to earlier versions if something goes wrong, and understand who changed what and why in a project.
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/3011888c-5884-4545-b9d0-79c9e3db66ee" />

 # Commands Executed 

git commit

git commit

This screenshots shows hoe commits are created in git 

C0, C1, C2, C3 are commits

Each circle represents one commit

The arrows show the order of commits

C0 → first commit

C3 → latest commit

main* shows that you are currently on the main branch, and it points to the latest commit (C3)

 # Introduction to Git Branch 

A Git branch is a separate line of development in a Git repository. It allows you to work on new features, fixes, or experiments without changing the main (working) code.

 # What is git checkout?

git checkout is a command used to switch between branches or commits in Git. When you checkout a branch, your working files change to match that branch’s code. It helps you move from one branch to another and work on different parts of the project easily.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/5eb7423d-266b-4243-88fe-7e439d8a766a" />

 # Commands executed

git branch bugFix

git checkout bugFix

Git branching works in a few simple steps. First, you start on the **main** branch, which contains the stable code. When you want to work on a new feature or fix a bug, you **create a new branch** using `git branch branchName` or directly create and switch using `git checkout -b branchName`.

Then you **switch to that branch** with `git checkout branchName` and make your changes safely without affecting the main code. 

After completing the work, you can **merge the branch back** into the main branch so that all changes are combined into the final project.

 # Introduction to Git Merging 

Git merging is the process of combining changes from one branch into another branch. It is usually used after completing work on a feature or bug-fix branch, to bring those changes back into the main branch. Merging helps keep all work together in one final version of the project without losing any changes.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/5c296a91-6b3b-48f4-a15f-16cb3b4e29e0" />

 # commands executed 

git branch bugFix

git checkout bugFix

git commit

git checkout main

git commit

git merge bugFix

 # (Git Merging – simple explanation)

This screenshot shows **Git merging** using the *Learn Git Branching* tool. First, a new branch called **bugFix** is created from the main branch, and a commit is made on the bugFix branch to fix an issue. 

Then, the user switches back to the **main** branch and makes another commit there. 

Finally, the command `git merge bugFix` is used to merge the changes from the bugFix branch into the main branch. After merging, the **main branch contains all commits from both branches**, showing how Git combines work done in different branches into one complete history.
 # Introduction to Rebase

What is Git Rebase

Git rebase is the process of moving or replaying commits from one branch onto another branch, changing the base commit so the history becomes linear.












