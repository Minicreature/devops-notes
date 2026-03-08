```
| Command | Use |
|---|---|
| `yum install git` | Install Git |
| `git version` | Check installed Git version |
| `git init` | Initialize a Git repo in current directory (creates hidden .git) |
| `git init repo_name` | Create + initialize a new repo with given name |
| `git status` | Check tracked/untracked files, staged changes, branch info |
| `git add filename` | Stage a specific file |
| `git add *` | Stage all changes in current directory |
| `git add file1 file2 ...` | Stage multiple specific files |
| `git commit -m "message"` | Commit staged changes with a message |
| `git remote add <name> <url>` | Link local repo to a remote repo |
| `git push <name> <branch>` | Push local commits to remote repo |
| `git push -u <name> <branch>` | Push + set upstream (use only first time for new branch) |
| `git clone <url>` | Clone remote repo locally (auto-adds remote as origin) |
| `git remote -v` | View all linked remote repos |
| `git pull <url>` | Pull latest changes from remote repo |
| `git log` | View commit history with messages and commit IDs |

## Key Concepts

| Concept | Meaning |
|---|---|
| `.git folder` | Hidden folder Git creates — stores all version history |
| `Staging Area` | Holding zone before committing — git add puts files here |
| `origin` | Default name given to remote repo when cloned |
| `-u flag` | Sets upstream — links local branch to remote branch permanently |
| `Local vs Remote` | Local = your machine, Remote = GitHub/GitLab etc. |
```
