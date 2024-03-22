•	git init: Initializes a new Git repository in the current directory.

•	git clone <repository_url>: Creates a local copy of a remote repository.

•	git status: Shows the current status of the working directory and staging area.

•	git add <file_name>: Adds changes in a specific file to the staging area.

•	git add .: Adds all changes in the working directory to the staging area.

•	git commit -m "Commit message": Commits changes from the staging area to the local repository with a descriptive message.

•	git commit -am "Commit message": Adds and commits changes in one step for modified files (skips the staging area).

•	git log: Displays a log of commits in the repository.

•	git log --oneline: Displays a condensed log of commits, showing only the commit message and hash.

•	git branch: Lists all branches in the repository.

•	git branch <branch_name>: Creates a new branch.

•	git checkout <branch_name>: Switches to a different branch.

•	git checkout -b <new_branch_name>: Creates and switches to a new branch in one step.

•	git merge <branch_name>: Merges changes from one branch into the current branch.

•	git pull: Fetches changes from a remote repository and merges them into the current branch.

•	git push: Pushes changes from the local repository to a remote repository.

•	git remote add <remote_name> <repository_url>: Adds a new remote repository.

•	git remote -v: Lists all remote repositories.

•	git fetch <remote_name>: Fetches changes from a remote repository without merging.

•	git reset HEAD <file_name>: Unstages changes for a specific file.

•	git reset HEAD: Unstages all changes from the staging area.

•	git reset --soft HEAD^: Undoes the last commit and keeps changes staged.

•	git reset --mixed HEAD^: Undoes the last commit and unstages changes.

•	git reset --hard HEAD^: Undoes the last commit and discards all changes.

•	git stash: Temporarily stores changes that are not ready to be committed.

•	git stash list: Lists all stashed changes.

•	git stash apply: Applies the most recently stashed changes to the working directory.

•	git stash pop: Applies and removes the most recently stashed changes.

•	git clean -n: Shows a preview of untracked files to be deleted.

•	git clean -f: Deletes untracked files from the working directory.
