Creating your own branch:
    git checkout -b nameofyourbranch

Switch to another branch
    git checkout nameofthebranch
    
Show your current branch
    git branch

Add your changes in staging status:
    git add nameoffile 
         OR
    git add . = add all changes

Record changes in repo
    git commit -m 'message'



BASIC PROCESS (Working on your own branch)
Step 1: Add Changes
    git add .
Step 2: Add message about the changes
    git commit -m 'message about your changes'
Step 3: Push to a specific branch
    git push -u origin nameofthebranch

