When creating a new project, create a new repository.
> mkdir project_name >
To initialise a git repo in the root of the folder.
> git init >
Create a new file.
> touch file_name.ext >
To see which files git knows exist - if you create a new directory but nothing inside, git will not register it. 
> git status
To add files to the staging environment (index).
> git add <filename>
To upload your files onto GitHub
> git commit -m "Useful message about what changes you have made"
Branches allow you to move between states of a project.
    eg. You can add a new page to your website without affecting the main part of the project. Once you are done, you can merge your changes into the primary branch. 
To create a new branch off the primary branch.
    git checkout -b <my branch name>
To push changes onto a new branch on GitHub - creates a new branch on the remote repo.
    git push origin yourbranchname
        when cloning a remote repo to local, git creates an alias, typically "origin".
Pull request alerts the owner that you want to make some changes to their code. 
Merge pull request will merge your changes to the primary branch.
It is advisible to remove old branches once they have been committed/ no longer needed. 
Hash codes are unique identifiers for that specific commit. Useful for referring to specific commits and when undoing changes - to backtrack. 
    git revert <hash code number>
When working in the primary branch, show all the files that have changed and how they've changed.
    git pull
See all new commits.
    git log
To switch back to the primary branch.
    git checkout master