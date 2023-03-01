# name and email
 commands :
 ## for name 
 git config --global user.name Amrit Mohapatra
 ## for email
git config --global user.email
## ls-lart shows all the folder including the hidden folders if a folder has a .git folder then it is a git repo
# status command
shows which files are staged and is there any modifications done to them 
# To stage a file :
use git add <file name>
ex :- git add pro1.html
# init command 
if creates a new .git folder
# git checkout 
matches your files with the last commit you have made usefull if you made some mistake
# git log command 
shows all the commits you have made and the authors of those commits
## if you want to see only a limited number of commits 
use git log -p -n ( where n is the number of last commits you want to view)
# git diff command
compare your working directory with your staged file 
# git commit -a -m <commit message>
skips the staging area and commits the changes directly
# rm command 
removes the file 
# git ignore 
ignores a file from commit 
used to exclude files like log file
# makeing a new branch
git branch <branch name >(type this to create a new brach)
git checkout <branch name >(to go to a branch)
git branch (to know which branch you are currently at)
# git merge 
first go to the master brach where you want to merge the other branch the type
git merge <branch name >
 then the mentioned branch will get merged with master branch
# Push command
1. add a remote repo by typing git remote add <name of the remote repo> <url of the repo on github>
2. then use git push <remote repo name> <branch name > to push the changes to a remote repo