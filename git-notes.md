\# Git Notes — Developer Handbook



\## 1. git init

Initializes a new local Git repository.



Example:

git init



\## 2. git clone

Copies a remote repository to your computer.



Example:

git clone https://github.com/USERNAME/REPOSITORY.git



\## 3. git status

Shows the current state of files in the repository.



Example:

git status



\## 4. git add

Stages changes for the next commit.



Example:

git add README.md



\## 5. git commit

Records staged changes in the repository history.



Example:

git commit -m "Add project documentation"



\## 6. git log

Displays the commit history.



Example:

git log --oneline



\## 7. git diff

Shows unstaged changes to tracked files.



Example:

git diff



To view staged changes:

git diff --staged



\## 8. git push

Uploads local commits to a remote repository.



Example:

git push origin main



\## 9. git pull

Fetches and integrates changes from a remote branch.



Example:

git pull origin main



\## 10. git fetch

Downloads updates from a remote repository without

integrating them into your current branch.



Example:

git fetch origin



\## 11. git branch

Lists local branches.



Example:

git branch



\## 12. git switch

Switches to another branch.



Example:

git switch main



\## 13. git switch -c

Creates and switches to a new branch.



Example:

git switch -c feature/documentation



\## 14. git remote -v

Displays configured remote repositories.



Example:

git remote -v



\## 15. git merge

Integrates changes from another branch.



Example:

git merge feature/documentation

