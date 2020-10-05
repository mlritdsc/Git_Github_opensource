#**A guide to Git, GitHub and Open Source**
##*This is a compilation of Git code from the Workshop conducted by Developer Student Clubs, MLRIT*

###**Setup**
*To set your name*

'''git
git config --global user.name "[name]"
'''

*To set your email Id*

'''git
git config --global user.email "[email id]"
'''

###**Creating a Repository**
You can create a Git repository two ways:

1. You can turn a local directory, which is currently not in Git to git as: 
'''git 
git init 
'''

2. You can clone a git repository from somewhere else like GitHub as
'''git 
git clone [url]
'''

###**Stage & Snapshot**

* To get the 'Status'

'''git 
git status
'''

* To stage files

'''git 
git add [file]
'''

* To Unstage a file

'''git 
git reset [file]
'''

* To commit a file

'''git 
git commit -m "[message]"
'''

###**Branch & Merge**

* To list out all the branches
'''git 
git branch
'''

* To create a new 'Branch'
'''git 
git branch [branch-name]
'''

* To 'merge' current branch to working directory
'''git 
git merge [branch]
'''

###**Updating the Remote Repo**
 To transmit local branch commits to the remote repository branch

 '''git 
git push [Add a git url] [branch]
'''