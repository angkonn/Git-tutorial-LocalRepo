<h1 style="color: red;">This is a readme file created from local machine.</h1>
Configure Git with your name and email (first-time setup):
# git config --global user.name "Your Name"
# git config --global user.email "your.email@example.com"

Initialize a local Git repository in your project folder:
# git init

Clone an existing GitHub repository to your local machine:
# git clone <repository-url>

Check the current status of your repository:
# git status

Stage specific files or all files for commit:
# git add <file>
# git add .

Commit the staged changes with a descriptive message:
# git commit -m "Your commit message"

Add a remote repository to link your local repository to GitHub:
# git remote add origin <repository-url>

Push your changes to GitHub (default branch main):
# git push -u origin main

Pull updates from the GitHub repository to sync with your local repository:
# git pull origin main

Create a new branch for working on a feature or task:
# git branch <branch-name>

Switch to the new branch:
# git checkout <branch-name>

Push the new branch to GitHub:
# git push -u origin <branch-name>

View the commit history:
# git log
# git log --oneline
