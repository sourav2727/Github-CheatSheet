### Git Command When you not adding README.md file
- git init
- git branch -M main
  //Renaming branch to main from default  master branch
- git branch 
  //for checking branch (optional)
- git remote add origin "Repositery Link"
- git push origin main


### If README.md is added to the Repositery 

  //first copy the url from code option 
- git clone "url"
- cd "folder Name"
- git status
  //it will show the status changed(modified)/unchanged(unmodified)/tracked/untracked
- git add .
//add all the files to the Repositery 
- git commit -m "any Message"
- git push -u origin main


#### If branch already exist shows
- git remote
- git remote remove origin
- git remote add origin "Repositery Link"
- git push origin main


##### when you do small changes in local repository and you want it in your remote repository  also,you do using this command
-git push
//under one condition while pushing -u should be added


### Branch
- git branch
// To check branch
- git branch -M branch-name
// renaming branch name
- git checkout -b new-branch-name
//Create and Switch to the New Branch
- git checkout branch-name
//switching existing branch to another branch
- git branch -d branch-name
// deleting existing branch
- git push origin --delete <branch-name>
//deleting a remote branch

### Merge
- git diff branch-name
// showing difference between existing branch and branch name that added in the command
- git merge branch-name
// merge two branch
- another way to merge is making a pull request

### Scenario
suppose you have two branchs and one is behind another , you make pull request on remote origin(github) and the branch which was behind another branch is now up to date.
and you want same thing happens with your loacl system,then you need to be on the branch you want to update, and you should use that branch's name in the command.
switch to the branch you want to update.
command goes like this------

- git checkout branch-name
//switching existing branch to another branch
- git pull origin (name of the branch you want to update)













