# GitLearning

Day1 :
--------------
GIT - VCS - version control system
 - to track changes in files / folders
        - to collaborate in teams
 - free and open source

Centralised VCS    |    Distributed VCS

GIT = DVCS

——————————————————

GIT HUB - website to upload your repositories online
  - provides backup 
  - provides visual interface to your repo
  - makes collaboration easier

GIT  !=  GIT HUB


Day2 :
-------------------
1. How to install Git on windows
2. Adding project/files to git for tracking
3. Git commands
4. Pushing project to remote repository(github)
_______________________________

Step 1 : check if git is already installed
             git --version

Step 2 : download and install git

Step 3 : add your project to git

Step 4 : commands

   git config --global user.email "yourGitHub@email.com"
   git config --global user.name "yourGitHubusername"

  - git init
  - git status
  - git add
  - git commit -m “…..”
  - git remote add origin <gitRepository>
  - git push -u origin master
  - git log
  - git —help

Step 5 : adding project to remote repository (github)


Creating Branches:
--------------------
1. What are branches
2. How to create branch
3. How to checkout branch
4. How to merge branch to master
5. How to delete branch (local and remote)
_________________________________________

Step 1 : Create branch 
   git branch “branch name”

Step 2 : Checkout branch
   git checkout “branch name”

Step 3 : Merge new branch in master branch
   git merge “branch name”

Step 4 : Delete branch
   git branch -d “branch name”    — delete from local
   git push origin —delete “branch name”   — delete from remote


Practicing:
---------------------

1) git config --list
	setup user.name , user.email
2) git config --global user.name ""
   git config --global user.email ""
3) git init -> will creat the folder as git folder
4) git status -> check status of all files
5) git add -> to add files to your account, but won't commit to master
6) git log 
7) git commit -m "first commit"
8) git checkout 'version' -> checkouts particular version
9) git checkout Master -> checkouts sources in Master Branch
10) git branch -> this will list all the branches branches available in the git account
11) git checkout -b "newBranchName" -> this will create a new branch with given branchname eg: branch1 and heade points to this branch
11) git checkout -b branch1 -> now header points to branch1 instead of Master
12) git commit -m "First Commit in the new Branch"

- Commit is not enough we need to push the commited files to particular branch.Master is default branch.
- To push the committed files to branch use
      git push -u origin <branchname>

13) git clone gitrepository link
14) git checkout --track



