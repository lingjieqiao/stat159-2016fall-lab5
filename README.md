# stat159-2016fall-lab5

User A: **Lingjie Qiao**

User B: **Kevin Liao**

## Task 1: Working on the master branch
In task 1, both userA and userB are working on the master branch (modify and push to master). At this point, there is no particular error/conflict because userA and userB made changes to the local repository after pulling the changes from master first, keeping the file constant and up-to-date on both users' directory.
![alt tag](https://www.atlassian.com/git/images/tutorials/collaborating/using-branches/02.svg)
This image is a good illustration of how both users are working with the master branch.

## Task 2: Resolving Conflicts
We got the error message saying "failed to push some refs to 'https://github.com/lingjieqiao/stat159-2016fall-lab5.git'." With hint saying "Updates were rejected because the remote contains work that you do not have locally." This is because User B does not have the changes User A made and pushed to the remote repository. In order to fix this problem, we should pull the changes from master first and make our own changes to the document. This will avoid the problem of having inconsistent materials between local and remote.

## Task 3: Working on multiple branches
We got a git notification saying "auto-merging failed - merge conflict." At this point, we should manually merge the two files in order to avoid conflict.

## Task 4: Both the users are on different branches
This step went pretty smoothly because the two users are working on different files on their different local branches. Since the user push the changes to the remote github repository after merging the branch on their local repository, there does not seem to be auto merging conflict from this step.

## Task 5: Both the users are on different branches w/ conflicts
Task 5 went much smoother than the previous tasks as we developed a better understanding of the merging system and branches. This task, user B was able to commit the changes to the remote github repository as everything is up to date. However, when user A was trying to push the changes she made on the local repository, she got the error message "failed to push some refs to 'https://github.com/lingjieqiao/stat159-2016fall-lab5.git'." The reason behind is that the remote contains work that you do not have locally, meaning the new changes user B made previously. 

## Some Final Reflections
We had a hard time monitoring the merging process at the very beginning as the changes in local files are sometimes not consistent with the remote github repository. The whole process created a lot of error messages that allow us to know better about github merging.  
