
# Git commands to be successful in life

### Quick steps for creating README.md file in a new repository

Create a local repository and initialise it using `git init`
Create a remote repository and clone it to move it to local and initialised at the same time.
Create a readme file, fill it in and save it.
Add it to staging with `git add .`
Commit the file to master put a description
Configure the push destination with `git remote add origin`
Set the upstream branch for current master and push with `git push --set-upstream origin master`

config --global --unset ked.mardemootoo@gmail.com
git config --global user.email ked.mardemootoo@gmail.com
git config --global user.name nocticdr
git config --list
git commit --amend --reset-author

Make changes
git add .
git commit -m "text"
git push


Step 1
### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone https://github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

Step 2
### Basic Commands

| Command | Description |
| ------- | ----------- |
| `code filename.tf` | Create a new terraform file called filename with extension tf |
| `git status` | Check status |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add -A` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes |
| `git rm -r [file-name.txt]` | Remove a file |
| `rm -rf [foldername]` | Remove a folder |

### Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin https://github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin https://github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |

### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View changes |
| `git log --summary` | View changes (detailed) |
| `git diff [source branch] [target branch]` | Preview changes before merging |
git remote -v

az account list
az account set --subscription "01. QL Enterprise Apps" 
cd packer
packer build azure-windows.json
Build 'azure-arm' errored: Cannot locate the managed image resource group tf-test.
az group create --name tf-test --location AustraliaEast 
