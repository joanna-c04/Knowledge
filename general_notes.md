# GitHub Commands
When creating a new project, create a new repository.
`mkdir project_name` </br>
To initialise a git repo in the root of the folder.`git init` </br>
Create a new file. `touch file_name.ext` </br>
To see which files git knows exist - if you create a new directory but nothing inside, git will not register it. `git status` </br>
To add files to the staging environment (index). `git add <filename>` </br>
To upload your files onto GitHub. `git commit -m "Useful message about what changes you have made"` </br>
Branches allow you to move between states of a project. </br>
>eg. You can add a new page to your website without affecting the main part of the project. Once you are done, you can merge your changes into the primary branch. </br> 
>
To create a new branch off the primary branch. `git checkout -b <my branch name>` </br>
To push changes onto a new branch on GitHub - creates a new branch on the remote repo. `git push origin yourbranchname` </br>
When cloning a remote repo to local, git creates an alias, typically "origin". </br>
Pull request alerts the owner that you want to make some changes to their code. </br>
Merge pull request will merge your changes to the primary branch. </br>
It is advisible to remove old branches once they have been committed/no longer needed. </br>
Hash codes are unique identifiers for that specific commit. Useful for referring to specific commits and when undoing changes - to backtrack. `git revert <hash code number>` </br>
When working in the primary branch, show all the files that have changed and how they've changed. `git pull` </br>
See all new commits.`git log` </br>
To switch back to the primary branch. `git checkout master` </br>

# Coding in C
## Introduction
### Structure
