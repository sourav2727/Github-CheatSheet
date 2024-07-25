### Git Command When you not adding README.md file
- git init
- git branch -M main
  //Renaming branch to main from default  master branch
- git branch 
  //for checking branch (optional)
- git remote add origin "Repositery Link"
- git push origin main


#### If branch already exist shows
- git remote
- git remote remove origin
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
- git push origin main

##### when you do small changes in local repository and you want it in your remote repository  also,you do using this command
-git push

###
- git checkout -b <new-branch-name>
//Create and Switch to the New Branch









