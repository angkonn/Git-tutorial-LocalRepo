Initial Setup
Configure Git with your name and email (first-time setup):
# git config --global user.name "Your Name"
# git config --global user.email "your.email@example.com"

Repository Setup
Initialize a local Git repository in your project folder:
# git init

Clone an existing GitHub repository to your local machine:
# git clone <repository-url>

Check the current status of your repository:
# git status

Staging & Committing Changes
Stage specific files or all files for commit:
# git add <file>
# git add .

Commit the staged changes with a descriptive message:
# git commit -m "Your commit message"

Linking to GitHub
Add a remote repository to link your local repository to GitHub:
# git remote add origin <repository-url>

Push your changes to GitHub (default branch main):
# git push -u origin main

Pull updates from the GitHub repository to sync with your local repository:
# git pull origin main



# Branch Commands

Check the current branch:
# git branch

Rename a branch:
# git branch -M main

Switch to an existing branch:
# git checkout <branch-name>

Create a new branch and switch to it:
# git checkout -b <new-branch-name>

Delete a branch:
# git branch -d <branch-name>