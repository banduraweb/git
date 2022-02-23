* git log --oneline
* git rm --cached .env
* git rm -f --cached .env
* git log
* git config --global user.name "bandura"
* git config --global user.email "bandura@..."
* touch app.js
* ls
* ls -a
* open . - mac
* start .
* clear
* pwd
* mkdir
* rm
* git rm -r --cached . 
* git rm --cached <file>
* git rm -r --cached <folder>
* rm file.js
* rm -rf folderName
* rm -rf .git
* git restore --staged fileName
* a vim insert
* git rm -r  --cached .idea
* git log --pretty
* git commit --amend
* git branch
* git switch
* git switch -create branchName
* git commit -a -m "msg"
* git branch -d branchName
* git branch -m newName
* git config --global core.editor "vim --nofork" // vim
* git merge --abort
* git stash
* git stash pop
* git stash apply * will save in history stashes
* git stash list
* git stash apply stash@{2}
* git stash drop stash@{2}
* git stash clear
* git log --oneline
* git checkout e6a23b8 * go to previous commit
* or git checkout HEAD~1 * step
* git switch - * back to current branch
* git checkout HEAD <file> * discard changes *not committed to state of previous commit
* or git checkout -- <file>
* git restore app.js *not committed
* git restore --source HEAD~1 app.js * committed
* git restore --staged secret.txt
* git reset 3533afea117a4d95a5dfcb30673efe4d44512dd6
* git reset --hard 3533afea117a4d95a5dfcb30673efe4d44512dd6 * remove also changes
* git revert 8b9f66e
* git branch -r * list remote branches
* git switch remoteBranch
* git fetch origin master
* git pull = git fetch + git merge
* test reset




#typeorm

* npm run typeorm migration:generate -- --name add-categories-for-questions -o
* npm run typeorm migration:generate -- -n initial-schema -o

