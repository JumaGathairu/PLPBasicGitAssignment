# PLPBasicGitAssignment
A hands-on assignment on Git and GitHub workflow

STEPS:
1. Open Git, create a new repository and initialize it with a readme file
2. Create a new folder on your local machine
3. Open a terminal or command prompt and navigate to the created folder
4. Initialize a new Git repository in your local folder using the command "git init"
5. Link your local repository to the Github repository using the command "git remote add origin <repository-url>"
6. Change branch from master to main
    git branch -m master main

7. Create a file instead your local folder, create a new text life and add a simple text message
8. Stage the changes in Gitbash using
    git add hello.txt
    git commit -m "Add hello.txt with a greeting"
9. Merge the local repository
    git pull origin main --allow-unrelated-histories
10. Pushing to GitHub
    git push -u origin main


