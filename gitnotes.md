
# If you don't do all these things in order, you wont actually edit the remote repository
# git add <file>
Easiest way to add file. Must add files that you changed and want to upload.
# git commit -m "notes on what you did"
Commits files you added or removed
 
# git push -u origin <branch>
actually updates online repository. master can be replaced with nay branch name

# git status
Shows what you are commiting andd if branch up to date

# git branch
See current branch you're working on
# git ls-tree -r <branch> --name-only
View all files in master repository

# git branch -m <new name>
rename branch

# update current branch to master files
git merge origin 