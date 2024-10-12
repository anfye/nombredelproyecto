Setting up a new Git Repo from the remote command shell
======================================================

## create a new repository on the command line
## using git version 2.47.0

    vi README.md
    
## Also created a text file to be in the repo
##
## Since using the git version more updated from the version 2.28.0, 
# this file will be updated after commit and push 

    git init -b main

## Now, let's add the files in the current directory in the local repository for commit.


    git commit -m "mi numero uno commit"
    git remote add origin git@github.com:anfye/newreponame.git
    git push -u origin master

## push an existing repository on the command line

    git remote add origin git@github.com:anfye/existingreponame.git
    git push -u origin master


#
#
# at least 3 left to none
