# Git Assignment - <zekiyerdem>

a. What is an issue?

An issue in GitHub is a tool for tracking tasks, enhancements, bugs, or discussions related to a project. It allows team members to report bugs, request features, or discuss problems with the repository.

b. What is a pull request?

A pull request is a request to merge changes from one branch into another, typically from a feature or development branch into the main branch. It allows for code review, discussion, and testing before the changes are integrated.

c. Describe the steps to open a pull request?

Create a branch: Work on your feature or fix in a new branch.
Commit changes: Once your work is complete, commit the changes.
Push branch to remote: Push your branch to the remote repository (GitHub).
Open a pull request: In the GitHub repository, go to the “Pull Requests” tab and click “New pull request.”
Select branches: Choose the branch you want to merge into the main branch.
Review and create: Add a title, description, and comments, then click “Create pull request.”

d. Describe the steps to add a collaborator to a repository (share write permissions)

Go to the repository page: Navigate to the repository on GitHub.
Settings: Click on the "Settings" tab.
Manage access: On the left side, click "Manage access."
Invite a collaborator: Click “Invite a collaborator” and enter their GitHub username.
Assign permissions: Once they accept the invitation, you can assign write permissions.

e. What is the difference between git and GitHub?

Git is a version control system that allows you to track changes in your code and collaborate with others. It operates locally on your machine.

GitHub is a web-based platform built on Git that allows you to store repositories online and collaborate with others via pull requests, issue tracking, and more.

f. What does git diff do?

git diff shows the differences between files or commits in your Git repository. It displays the changes that have been made in the working directory that have not yet been staged or committed.

g. What is the main branch?

The main branch is the default branch where the production-ready code resides. It’s usually the most stable branch of the repository.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

No, it's generally not recommended to push changes directly to the main branch. Best practices involve creating feature or development branches for your work, reviewing the code through a pull request, and then merging it into the main branch after approval. This avoids potential bugs or unstable code being pushed directly into production.