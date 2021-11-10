# GitCheatSheet

* Initial commands to push first commit<br>
__________________________________________ <br>
git init <br>
git add .  <br>
git status <br>
git commit -m "Write your commit message" <br>
git branch -M main <br>
git push -u origin main <br>

* Push changes to github <br>
__________________________________________ <br>
git add .  <br>
git status <br>
git commit -m "Write your commit message" <br>
git push -u origin main <br>

* Pull changes from github <br>
__________________________________________ <br>
git pull  <br>

* branch (list, create, change, update, delete) <br>
__________________________________________ <br>
git branch  <br>
git branch new-branch <br>
git checkout new-branch <br>
git push origin new-branch <br>
git push -d origin branchname  (deletes locally) <br> 
git branch -d branchname  (deletes remote branch) <br>

* Get changes from one branch to another branch <br>
__________________________________________ <br>
git checkout main <br>
git pull origin new-branch <br>
git push origin main <br>

* Revert to specific commit in git and github <br>
__________________________________________ <br>
git log  (To get commit id)<br>
git reset --hard commitId (Give commitId from where you want to continue)<br>
git push -f origin branchName (Done)<br>
