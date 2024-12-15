# git-commands

| Command | Description |
| --- | --- |
| `git status` | List all **new or modified** files |
| `git add <file-name or directory>` | Stages a file or files in a directory|
| `git add -p <file-name or directory>` | Stages the selected parts of a file|
| `git restore --staged <file-name or directory> ` | Unstages a file or files in a directory|
| `git commit -m "Message"` | Commit **staged files** with message |
| `git commit --amend -m "New commit message."` | Change the message of the last commit that is not yet pushed|
| `git push origin` | Uploads your **commits** to github |
| `git pull origin` | Updates your **local-branch** |
| `git remote show origin` | Shows the **details** of branches |
| `git diff` | Show file differences that **haven't been** staged |
| `git reset --hard HEAD~1` | Deletes the **unpushed** commit |


## git stash commands
| Command | Description |
| --- | --- |
| `git stash` | Stores the changes aside |
| `git stash push -m "custom message"` | Stash with custom message |
| `git stash -u` | Store the changes aside including the **untracked** files |
| `git stash list` | List all the stash |
| `git stash apply <stash-index>` | Retrieve the stashed changes to the current branch |
| `git stash show <stash-index>` | Show the changes in that stash |
| `git stash show -p <stash-index>` | Show the changes in that stash in full tree view |
| `git stash branch <branch-name> <stash-index>` | Create a branch from a stash |
| `git stash pop` | Retrieve the latest stash to the current branch |
| `git stash clear` | Remove all the stash |


## git branch commands
| Command | Description |
| --- | --- |
| `git branch` | Lists all of the branches in the repository (the same as git branch --list). |
| `git branch <branch>` | Creates a new branch called <branch> but does not checks out the new branch. |
| `git branch -d <branch>` | Deletes a branch. If there are unmerged changes, Git does not allow you to delete it. |
| `git branch -D <branch>` | Forces delete the branch, even if there are unmerged changes. Execute this command when you are sure to delete it permanently. |
| `git stash apply <stash-index>` | Retrieve the stashed changes to the current branch |
| `git stash show <stash-index>` | Show the changes in that stash |
| `git branch -m <branch>` | Moves or renames the current branch to <branch>. |
| `git branch -a` | Lists all the remote branches. |
| `git checkout -b <branch>` | add a new branch named <branch> and then move to that branch |
