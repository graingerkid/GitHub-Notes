Repository
============
A repository is basically a directory, this is your collection of files which
stores each commit you pushed to github. Every file in your repository is saved
on each commit regardless of whether they were changed or not. So if you have two
files and only one changed they are both still saved in a snapshot on a commit.

Github Notes
============

To clone a repository:

git clone <repo URL>


To see differences in the terminal after you have changed a file:

git dif


To check the status of files use:

git status


To submit changes, use the following 3 stages...

First add the files, checking the *status on this will now show that are ready
for commit:

git add <file name>


Next we commit the files and add a commit message, what changes we made:
git commit -m "this is the commit message"


Finally we push the changes from our local repo to github:
git push


The difference between the 3 stages are as follows:
===================================================

git add <file name> - Here we are telling git to begin tracking changes to a file.

git commit -m "this is the commit message" - Here we are storing the chagnes

git push - Here we are saying, anything committed and ready to go will be pushed
to our github repo.


View all commit messages
========================
git log

To see the difference between two commits, you can copy each commit id and use
git diff to show the differences, exmaple:

git diff e00f8a19b563e74e0ff1b1f3f6e9552ec463c409 d157433310b6d34ef88a71e086c1ecf1720595e1

Add the flag --stat to see which files in the commit were changed

Create a new Branch
===================

git checkout -b [name_of_your_new_branch]

Push the branch on github:

git push origin [name_of_your_new_branch]


Change Branch
=============

git checkout <branch name>
