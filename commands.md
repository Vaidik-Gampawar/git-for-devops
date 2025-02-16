# Git Commands Guide

## 1. Repository Setup  
- Initialize a new Git repository: `git init`  
- Check the current working directory: `pwd`  
- List all files, including hidden files: `ls -a`  

## 2. File Management  
- Create a new file: `touch filename.txt`  
- Remove a file: `rm filename.txt`  
- Open and edit a file in Vim: `vim filename.txt`  

## 3. Staging and Committing  
- Check the status of the repository: `git status`  
- Add a file to the staging area: `git add filename.txt`  
- Remove a file from the staging area: `git rm --cached filename.txt`  
- Commit changes with a message: `git commit -m "commit message"`  

## 4. Configuring Git  
- Set the global username: `git config --global user.name "Your Name"`  
- Set the global email: `git config --global user.email "your.email@example.com"`  

## 5. Branching  
- Create a new branch: `git checkout -b branch-name`  
- Switch to another branch: `git checkout branch-name`  
- List all branches: `git branch`  
- Switch branches using Git switch: `git switch branch-name`  

## 6. Logs and History  
- View commit history: `git log`  
- View commit history in one line: `git log --oneline`  

## 7. Restoring and Undoing Changes  
- Restore a deleted file: `git restore filename.txt`  

## 8. Checking Git History  
- View the command history: `history`  

---
