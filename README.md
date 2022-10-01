# Git and Github Commands
1) git config --global user.name "xyz"
   git config --global user.email "xyz@gmail.com"
    -> To create a git account and use this on github to login.
    Use global to set the username for every repository you create
    git --version to check the git version installed
2) mkdir -> create a new directory 
3) cd -> to change the current working directory
4) git init -> to create a empty git repository in the specified folder 
How to check if it is a git repository?
So it has created a hidden file .git inside your folder which can be seen by command ls -la
5) git status -> to check the status of the file if it is part of our repo or not 
git status --short -> To see status in a shorter format
i) Tracked files  ii) Untracked files iii) Modified files
6) git add . or filename or --all -> To add the untracked file to the repo but yet are to commited to the repo(Just added)
7) git commit -m "Placeholder" -m "Description"-> To commit the changes made to the repo and reflect it in local machine not at github
git commit -am "Placeholder" -m "Description"-> To commit and add the changes made to the file at once to a modified file
8) git clone sshlink -> this will clone the repository into your folder 
9) git log -> to view the commits history for the repository
10) git help --all -> to get help for the command 
If you find yourself stuck in the list view, SHIFT + G to jump the end of the list, then q to exit the view.
11)SSH Keys
SSH Keys are unique keys with which you can connect to github without any user name or personal access token at each visit.
12) git push -u origin master -> To finally push the files to the github repo
13)git remote add origin (link of repo from github)
14) git remote -v -> To check if it is linked to any repo or not 
15) Fork to get another person repo into your repo
16)git branch -> to get list of all the branches
17) git checkout -b newbranch -> to create a new branch and switch between branches
18) git diff branchname-> to check difference between both the branches


