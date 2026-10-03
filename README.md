# git-lab1-angelochiong
lab1
Question 1
Git basically sees the 2 files that have been created, but is not tracking these yet. Without git add . , Git doesn't know what do with those files.

Question 2
git diff reads and tells us exactly what the changes in the files are. It shows both file changes separately, clearly marking what the changes are with the red colored texts.

Question 3
git restore lets us restore a file back to its previous version, the commited version. In this step, we removed a line from the goals.txt file, then used git status to check what changed that has not been commited yet, then restored it.

Question 4
The big difference to git restore versus git revert is whether or not the changes has been commited. Referencing question 3; git restore lets us restore a file with changes that has not been commtied yet back to its previous commited version.

On the other hand, git revert is what we need to fix our mistake if we did do a commit that was not intended. Although, it does not delete the "wrong" commit, it makes a new commit on top of it. Basically:

Commit A 
Commit B - incorrect or unwanted commit
Commit C - back to Commit A, but creates another commit instead of deleting commit B and going bakc to Commit A