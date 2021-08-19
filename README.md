# Samples

### clone a repo to your machine 
- git clone https://github.com/amrutapatilAI/GitCommandsDemo.git
### create new branch 
- git checkout -b newbranchname
###  checke uncommite and unpushed file
   -  git status
- here when you file names in red color .It indicates that files are still untacked and still have to be commited 
- while as green colored files indicates that files are commited but you have not pushed them in the Repo.
### steps to push your code to the repo.
 ####  first add untracked files to the git 
     - git add <filename>   - this will chnege your files color from red to green
 ####  next commit your files 
     - git commit -m "you commit message"
 #### and the last step is push it to the repo
     - git push origin <your barch name>
     
 ### steps to pull updated  code to your branch
 #### make sure your current repo is clean to avoid conflicts
     - git stash      #this will remove all your local chanes wich are uncommited for time being 
