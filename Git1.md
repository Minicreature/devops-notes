Git -
Git is a version control tool used for tracking a systematic changes in one or more branches in isolated environment locally.

yum install git
git version

git init -- initializing git repo. it creates hidden repo .git in pwd.
git init repo_name -- will create a repo if not available, and then initialize it.

git status -- to check tracked/untracked changes made, branch, staged changes & commit area.

git add filename -- to move a perticular change to staging area.
git add * -- to move all changes in pwd to staging area
git add file1 file2 ... -- to move only mention changes to staging area

git commit -m "Commit Message" -- to commit all staged changes to a new version. '-m' is used for add provided message to version for our future referance.

Remote Git Repo -
It is cloud based environment when multiple users can track changes same as git but on remote repo.
e.g. GitHub, GitLab

git remote add <name> <url> -- This will let the local system know there is remote repo with this name. Origital name of the repo on remote does not have any direct impact on name mentioned locally (only for our reference).

git push <name> <branch> -- This will push the current version locally available as it is to the remote repo.
git push -u <name> <branch> '-u' option is used only first time while introducing a new branch at remote repo.

git clone <url> -- It will clone everything from remote repo to local repo. This mostly used first time while intrducing a new repo locally. This will also add remote repo details to local automatically.

git remote -v -- To check all available remote repo details locally. 'origin' is the name given to a remote repo after cloning by default.

git pull <url> -- Will only pull the new changes made from remote repo.

This is for your reference claud - We will only focus on these topics the detailed course is where we can do detailed stuff. I have done the labs break & stuff is not required.
I am using laptop. Only provide notes as per my required format. No File required. Only text in the chat as in reuired format.
