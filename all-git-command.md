1. Initializing a Git Repository:
   - `git init`: Initialize a new Git repository in the current directory.

2. Basic Git Commands:
   - `git add <file>`: Add a file or changes to the staging area.
   - `git commit -m "<message>"`: Commit the staged changes with a descriptive message.
   - `git status`: Show the status of your working directory and staging area.
   - `git log`: Display the commit history.

3. Branching and Merging:
   - `git branch`: List all branches in the repository.
   - `git branch <branch-name>`: Create a new branch.
   - `git checkout <branch-name>`: Switch to a different branch.
   - `git merge <branch-name>`: Merge changes from one branch into the current branch.
   - `git remote`: List all remote repositories.
   - `git remote add <remote-name> <remote-url>`: Add a remote repository.
   - `git push <remote-name> <branch-name>`: Push local commits to a remote repository.
   - `git pull <remote-name> <branch-name>`: Fetch and merge changes from a remote repository.

4. Working with Remote Repositories:
   - `git clone <repository-url>`: Clone a remote repository to your local machine.
   - `git fetch`: Download objects and refs from a remote repository.
   - `git pull`: Fetch and merge changes from a remote repository.
   - `git push`: Push local commits to a remote repository.

5. Undoing Changes:
   - `git revert <commit-hash>`: Create a new commit that undoes the changes made in a previous commit.
   - `git reset <commit-hash>`: Reset the current branch to a specific commit, discarding all commits after it.

6. Additional Git Commands:
   - `git diff`: Show the differences between the working directory, staging area, and the last commit.
   - `git tag <tag-name>`: Create a new tag for a specific commit.
   - `git stash`: Temporarily save changes that are not ready to be committed.