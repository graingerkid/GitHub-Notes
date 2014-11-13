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