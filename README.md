# Creating a project for GitHub named Raji-Project

Steps to follow create repository
1. Create a directory or project in the folder
2. git init (command) - Initialized empty Git repository in the created directory or folder path
3. Create files in the folder
4. git status (command) - No commits yet and shows all the files as "U" -untracked files
5. git status -s (command) - Short description of the file status
6. create gitignore - you can enter the file names which you don't want to include in this repository
7. git add . (command) - add all the files in the repository (all files changed from "U" to "A")
8. Edit the file - eg -edit README.md (the file changed from "A" to "M" means not staged)

# Steps for committing the repository
9. git status (command) - to update the changes in the file it will ask to restore (means old version) or add (chnged version)
10. git restore filename (command) (eg-README.md) - changes won't take effect and old version stays as it is. (And the file changed from "M" to "A")
11. git add filename (command) - whatever the changes happened it will be updated (file changed to "A")
12. git commit -m "message" (command) - message - you can enter the message as why the change has been made
13. Now all the files are committed in that repository. (Nothing will be displayed in file menu)
14. git status (command) - to check the status. Now it will show as "On branch master nothing to commit, working tree clean"

# Note
If you forget to put the -m flag when you are commiting it will open the editor message file as which file has been modified (This file is opened from the .git file)
Give a message in the header and save it. Then close the file

# Changing default branch name (from master to main)
git branch -m master main
pushing this to remote
git push -u origin main

# Reference link
https://www.youtube.com/watch?v=CvUiKWv2-C0