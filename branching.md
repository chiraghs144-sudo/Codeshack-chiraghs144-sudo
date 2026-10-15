\# Git Branching and Collaboration



\## What Is Branching?



Branching allows developers to work on different features

without directly changing the main branch.



\## Why Are Branches Useful?



\- Developers can work independently.

\- Changes can be reviewed before merging.

\- Multiple features can be developed in parallel.

\- The main branch stays organized.



\## Create a Feature Branch



&#x20;   git switch -c feature/my-feature



\## Check Your Current Branch



&#x20;   git branch



\## Stage and Commit Changes



&#x20;   git add .

&#x20;   git commit -m "Add a new feature"



\## Push a Feature Branch



&#x20;   git push -u origin feature/my-feature



\## Fetch Remote Changes



&#x20;   git fetch origin



\## Pull Remote Changes



&#x20;   git pull origin main



\## Collaboration Workflow



1\. Start with the latest main branch.

2\. Create a separate feature branch.

3\. Make and commit changes on that branch.

4\. Push the branch to GitHub.

5\. Open a pull request for review.

6\. Merge changes after approval.



\## Important Rule



Avoid committing directly to main when a project requires

feature branches and code review.

