# Git Commands
Setup
Initialize a new Git repository: git init

# Set the default branch name to 'main': git branch -m main

# Status
Check the status of your working directory and staging area: git status

# Creating and Modifying Files
Create a new file: vim <filename>.txt

# Remove a file from the staging area: git rm --cached <filename>.txt

# Adding Changes
Add changes to the staging area: git add .

# Commit changes with a message: git commit -m "your message"

# Branching
Create a new branch: git branch -b <branchname>

Checkout a branch: git checkout <branchname>

Merging and Rebasing
Merge branches: git merge <branchname>

Rebase branches: git rebase <branchname>

Pushing and Pulling
Push changes to a remote repository: git push origin <branchname>

Pull changes from a remote repository: git pull origin <branchname>

# Remote Repositories
Add a remote repository: git remote add origin <url>

Verify remote repositories: git remote -v

# SSH Keys
Generate SSH keys: ssh-keygen

View the public SSH key: cat ~/.ssh/id_25519.pub

# Viewing History
View commit history: git log

Reset and Restore
Remove a file: rm <filename>.txt

Restore a file from the working directory: git restore <filename>.txt

# Configuration
Configure user name: git config --global user.name "your name"

Configure user email: git config --global user.email "your email"

# Creating a New Directory
Create a new directory: mkdir <directoryname>

# Viewing Contents
List files and directories: ls

List all files including hidden ones: ls -a


