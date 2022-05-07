# This is a Cheat-Sheet with WSL and Git commands:


### To start git:
`git init`


### To clone repository from GitHub:
`git clone (url from project on your github)`


### To check the status of project:
`git status`
Enables you to see the files that are changed in your project


### To add directory that I want to save changes (have to input directory without ''). File goes from Untracked (U) to Staged
`git add <file name (when inside project folder)>`


### To commit changes. Tells git to approve the changes that were added in staged:
`git commit -m "MESSAGE" `


### To push changes to remote repository:
`git push`


### If error when trying to push commit try to run the following:
`git push --set-upstream origin main`


### If error persists try the following before pushing:
`git config --global init.defaultBranch main`


### To pull the changes available in remote repository:
git pull 


### Create `.gitignore.txt` file that points to the folder I want git to ignore:
write inside the file: `venv/` (to ignore the venv directory)


### To create a virtual environment:
`python3 -m venv venv`


### To access the virtual environment:
`. venv/bin/activate`


### To close the virtual environment:
`deactivate`


### Create the folder `requirements.txt` in the root of the project to store al the projects' dependencies:
Write inside the packages and point to the version of it as follows:
`pandas==x.x
django==4.0.1
etc...`


### To install everything at once from the `requirements.txt`, run the command:
`pip3 install -r requirements.txt`


### To force delete a folder or file from within a repository:
`rm -fr 'file or folder name'`
