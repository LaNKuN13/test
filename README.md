test the commit push to the github

# set the user name
git config --global user.name "xxx"

# set the user email 
git config --global user.email "xxx@gmail.com" 

# check the git version
git --version

# create a new file of the file changing
git init

# clean the terminal
clear

# check the status on the branch main
git status

# three ways to add
git add filename.md

# add all .md file
git add *.md 

# add all changes into staging area
git add .

# commit
git commit -m "message that explains this time commit"

# show the history of the commit (use q can quit)
git log

# simplified version
git log --oneline

# check the changing on the files
git diff ID -- file.md

# return to the previous version (after return need to commit again)
git check ID -- file.md


