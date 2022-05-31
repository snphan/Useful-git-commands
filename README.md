# Useful-git-commands

**Pull and Track a branch on Github**

    git branch -f [branch_name] origin/[branch_name]


**Pull from main while in a branch**

    git pull origin main


**Move existing, uncommitted work to a new branch in Git**

    git switch -c <new-branch>

**Untrack a file after you add it to .gitignore

    git rm --cached database.db
