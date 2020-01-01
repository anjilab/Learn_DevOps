Git step 1)
1) git init : initialization of git in your project
2) git status : checking the status of file. are files being tracked or not
3) git add : to make files tracked i.e being in stage area.they are not saved but are staged
4) git commit : meaning they are being saved now.photo khichera sakyo (git commmit -m "message"
5) git remote add origin : syncing to remote repository.i.e you are gonna add your code/files from your local to remote computer/repository
6) git push origin master : pushing your code/files from local computer to remote computer/repository
7) git clone : In order to download remote repository to your local ones,you need git clone <url>.
8) git pull origin master : inorder to get all the changes pushed in remote master to be shifted in your local then we need to pull those changes.
9) git branch branchName : For parallel development,in a project,many developers so to collaborate,branching is done. 
10) git branch -D branchName : to delete branch
11) IMPORTANT POINT : when you do git branch <branchName>, then the last commit of your master becomes,the first commit of branch you created
=============================================================================TAKE A BREAK==============================================
12) git log: In your repo,if you want to know about everything i.e about every commit most important command is git log.It not only tells you about your branch commits but all of your commits.
13) git stash : when working with multiple branch sometimes you have to switch between branches. WE USUALLY COMMIT AFTER ACTUALLY FINISHING COMPLETE FEATURE,BUT SOMETIMES IF WE HAVEN'T COMPLETED THAT FEATURE IN CERTAIN BRANCH BUT YOU NEED TO GO TO ANOTHER BRANCH BECAUSE OF EMERGENCY THEN WITHOUT COMMITING YOUR WORK YOU CAN GO TO THE BRANCH THAT WAS EMERGENCY FOR THAT WE USE GIT STASH.
When you don't want to save your incomplete work in repository,to stash your staged files,i.e after doing git add we use git stash so there is no need for commit after finishing that emergency case we can come back to the working branch and get all the incomplete changes by git stash.
===========================================================NEXT BREAKKK======================================================

14) git revert : reverting a commit,to a previous version. git revert -hashidOfCommit
I want to got back to my first commit of particular branch to do that we do git revert commitId. 
git revert commitID when you do, the changes which you have done in that commit are deleted.while being deleted it leave revert message so that we can again revert back.to revert back YOU DO GIT CHECKOUT COMMITIDTOBEREVERTBACK
when you do git revert commitId,AND DID 'ls command' the file/code you had entered will not be seen after doing ls.
BUT HOW TO UN-REVERT THE REVERT 
same after  reverting it leaves a commit with the same commit id you can revert back so the previous changes deleted from revert can again be obtained back by revert.
