#Git Tutorial (Continued)
##1. Adding files to the staging area
Command: git add .

The git add command adds all changed files from the working directory to the staging area. The staging area is a temporary storage area before committing.

Notes:

You can use git add <file_name> to add specific files to the staging area.
Use git add -A to add all changed and new files to the staging area.
##2. Committing files
Command: git commit -m "git init"

The git commit command saves the files from the staging area to the local repository.

Parameters:

-m: Commit message.
Notes:

Commit messages should be short and concise, describing the changes made.
##3. Creating a remote repository on Github
Go to Github.com and sign in to your account.
Click the "New Repository" button.
Enter the repository name as "git-tutorial".
Select "Public" or "Private" depending on your needs.
Click the "Create Repository" button.
##4. Linking the local repository to the remote repository
Commands:

git remote add origin git@github.com:your-account/git-tutorial.git
git branch -M main
git push -u origin main
Explanation:

git remote add origin git@github.com:your-account/git-tutorial.git: Add a remote repository with the name "origin" and the URL as https://www.youtube.com/watch?v=lOeQUwdAjE0.
git branch -M main: Rename the current branch (master) to main.
git push -u origin main: Push the main branch to the remote repository "origin".
Notes:

Replace your-account with your Github username.
##5. Checking the current branches
Command: git branch

The git branch command shows a list of the current branches in the local repository.

Output:

* main
##5. Creating a new branch
Command: git checkout -b branch_name

Example:

git checkout -b abc
The git checkout -b branch_name command creates a new branch with the name branch_name and switches to that branch.

13. Checking the newly created branch
Command: git branch

Output:

* abc
main