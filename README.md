# git-commands

| Command | Description |
| --- | --- |
| `git status` | List all **new or modified** files |
| `git add <file-name or directory>` | Stages a file or files in a directory|
| `git restore --staged <file-name or directory> ` | Unstages a file or files in a directory|
| `git commit -m` | Commit **staged files** with message |
| `git commit --amend -m "New commit message."` | Change the message of the last commit that is not yet pushed|
| `git push origin` | Uploads your **commits** to github |
| `git pull origin` | Updates your **local-branch** |
| `git remote show origin` | Shows the **details** of branches |
| `git diff` | Show file differences that **haven't been** staged |

## git stash commands
| Command | Description |
| --- | --- |
| `git stash` | Stores the changes aside |
| `git stash -u` | Store the changes aside including the **untracked** files |
| `git stash list` | List all the stash |
| `git stash apply <stash-index>` | Retrieve the stashed changes to the current branch |
