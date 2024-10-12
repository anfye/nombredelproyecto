Setting up a new Git Repo from the remote command shell
======================================================

"create a new repository on the command line"
## was not so simple knowing almost less than nothing 
This do-it-for-myself task really helped me getting ready to start as a total beginner.

Although I just mentioned as a task right above, it was a lot more like a project. This really taught me how far I am from knowing something. Anyhow, I am glad that I am actually going through this how although it's very late.

## To be able to start using git requires many prerequisites!
Specially for people like myself, who wants to jump start, reading blogs and many websites explaining to help others to learn were too vague. All scattered information actually made this ignorant person imagining learning. It's very sad. At least, this is my story.

Step by step, I will try to write down from my experience.



Whatever written below is total garbage mumblings. Please disregard for now.
================================================================================
## SOON TO BE UPDATED !

#
#
#
#
###########################################################################

using git version 2.47.0

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
