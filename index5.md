Aim

To upload a local project to GitHub, make a second commit, and verify the commit history.

Steps Performed

1. Create a GitHub Account

I created a GitHub account on GitHub or used my existing account to access GitHub services.

2. Create a New Public Repository

I created a new public repository named web-development-practice on GitHub.

3. Connect the Local Repository to GitHub

I opened the terminal inside my local project folder and connected it to the remote GitHub repository.

Commands used:

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/web-development-practice.git
git push -u origin main

Note: Replace YOUR-USERNAME with your actual GitHub username. If the project is already a Git repository or the remote is already configured, do not repeat the corresponding initialization or remote command.

4. Upload Files Using Git Push

I uploaded my local project files to GitHub using the git push command. The files became available in my public repository.

5. Add a New File and Push the Second Commit

I created a new file named README.md and added the project description.

Content of README.md:

# Web Development Practice

This repository contains my web development practice
and assignments.

## Topics
- HTML
- CSS
- JavaScript
- Git and GitHub

Then I ran the following commands:

git add README.md
git commit -m "Add README file"
git push

6. Verify the Commit History

I checked the commit history using the following command:

git log --oneline

I also opened my GitHub repository and checked the Commits section to verify that both commits were uploaded successfully.

Result

I learned how to create a public GitHub repository, connect a local project to GitHub, upload files using Git, create a second commit, and verify the commit history.

Submission

Public GitHub Repository Link:
https://github.com/YOUR-USERNAME/web-development-practice