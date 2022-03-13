
### 15 essential commands to use git

https://towardsdatascience.com/15-git-commands-you-should-learn-before-your-very-first-project-f8eebb8dc6e9#

* git init: This command is used to set a folder as a github repo so that GIT can track changes to files
* git add README.md: This command adds the modified files to the staging area to be ready for the commit
* git log origin/master --oneline: It tells you the commit history so far
* git remote add origin url: Adds the remote repository link
* git remote -v: Shows the remote origin links

* git stash push -m "Why stashing": Moves modified to stashing area
* git stash pop: Reaaplied modifications to files

* git remote show origin: status of origin

* git fetch origin master: Download remote commits and changes
* git pull origin master: Pull the changes to local 
* git checkout [-b] origin/master
* git diff HEAD origin/master
* git merge origin master

* git reset --hard HEAD~1

* git branch: show branches [-a -r]
* git branch -d deleted

Go to master and merge, then push to origin

git checkout master
git merge branch
git push origin master
