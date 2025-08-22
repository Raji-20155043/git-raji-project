# Add steps for Branching and Merging

1. git branch "branchname" (command) - "branchname" - name for your new branch 
    origin branch will be master
2. git log (command) - check the log events and the header statement will be 
    (HEAD -> master, branch-merge) or (HEAD -> master, origin/master, branch-merge) -- branch-merge is the new baranch name
3. git checkout newbranchname (branch-merge) (command) - It will be switched to new branch called "branch-merge"    
    from master
4. create a new file and write down
5. Commit the new file
    git add . (command) - adding the files
    git commit -m "message"  (command) - new file committed
    git log (command) - to see the log events 

6. switched back to master branch by entering the command git checkout "branchname" (master)
7. created another new file in the master branch and committed the files
8. Switched back again to "branch-merge" branch and committed the changes

 

# Reference link

https://www.youtube.com/watch?v=Q1kHG842HoI