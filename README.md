
**Commands**

git config --global user.name [username]   configure email and name
git config --global user.email [your email]  ---config email
git config user.name --view name
git config user.name --view email
git add [folder/file] ---to add file or folder to be commited in the staging area
git init [on the current directory ] --to intialize the git repo
git reset <filename> -- undo the add operation
git log --to view the checkpoint graph or to view all commit which have made
git commit -m "message"  ---to commit a staging stack to commit
git branch --->to view the branch
git branch <branch-name>  --->to create a new branch
git switch -c <branch-name> --->to create and switch
git commit -a -m <message> -->to commit and add
git branch -D <branch-name> ---->to delete the branch
git branch -m <branch-name> --->to rename the branch
git merge <branch name>
git reset --hard HEAD~1
git diff ---to see the changes made before staging
git diff HEAD ---> include both staged and unstaged unchanges
git diff --staged
git diff --cached
git diff HEAD [filename]
git diff --staged [filename]
git diff branch1 ..branch2
git diff <commit hash1> commit hash2>
git stash ---->to save the changes in a branch
git stash pop --->to pop the saved changes
git stash apply --->to apply to the multiple branch
git stash list  ---->to show the list
git stash apply stash@{2} --->to apply particular stash to the branch
git stash drop stash@{2} ---> to drop the particular stash
git stash clear
git checkout HEAD~1 --->too traverse the  node
git checkout HEAD <file> to revert the file from previous commit
git checkout -- <filename> -->to revert the file from previous commit
git restore <filename> --to restore the file back
git restore --staged <filename> --to restore the staged file back
git restore --source HEAD~5 <filename> -->multiple files time travel
git reset <commit-hash> --> regular reset
git reset --hard <commit-hash> --.hard reset -->to reset the commit
git revert <commit-hash> --->new commit after the bad commit

[after setting up ssh key]
git remote -v  --->to check the connection between git and github
git remote add origin [url of repo]

git push origin master --> to push the repo to the github

