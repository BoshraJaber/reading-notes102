# Git Tutorial: A Comprehensive Guide

## Version Control:
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. 
1. Local Version Control: A Local VCS entails one database on your hard disk that stores changes to files.
2. Centralized Version Control: his system entails a single server storing all changes and file versions, which can be accessed by various clients.
3. Distributed Version Control: A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure.
 
 ## What is Git?
 * Git is a DVCS that stores data in a file system made up of snapshots. 
 * Git mostly relies on local operations because most necessary information can be found in local resources.
 * Git track every single change applied to any file or directory.
 * Git is set up to greatly minimize the possibility of irreversible damage to files.
 * Files in Git can reside in three main states: committed, modified and staged.
 ![vv](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)
 
 ### Initial Customization;
 * *git config* allows the setting of configuration variables that control aspects of Git’s operation and look.
 * *git help command* to access the help manual.
 
 ### Setting up a Git Repository:
 
 #### Importing:
 1. $ cd test (cd = change directory): Switch to the target project’s directory.
 2. $ git init
 3. $ git add *.c
 4. $ git add LICENSE.
 5. $ git commit -m “any message here".
 
 #### Cloning:
 $ git clone https://github.com/test
 
 #### Check File Status:
 $ git status
 
 #### Tracking and Staging a New File:
 * $ git add *
 * $ git status
 
 #### Commit a file:
 $ git commit -m “made change x,y,z”
 
 #### Pushing Changes:
 $ git push origin master
 
 #### Seeing Your Remotes:
 $ git remote -v
 
 ##### Fetching:
 git fetch [remote-name]
 
 #### Pushing: 
 git push [remote-name][branch-name
 
 #### Deleting Branches:
 $ git branch -d test
 
 #### Preview Changes:
 git diff <source_branch> <target_branch>
