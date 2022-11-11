# Useful-git-commands

**Pull and Track a branch on Github**

    git branch -f [branch_name] origin/[branch_name]


**Pull from main while in a branch**

    git pull origin main


**Move existing, uncommitted work to a new branch in Git**

    git switch -c <new-branch>

**Untrack a file after you add it to .gitignore**

    git rm --cached database.db

**Undo a commit to HEAD~1 while preserving changes with --soft**

    git reset --soft HEAD~1

**Git Stash just one file**
    
    git stash -- [filename]
    
**Exclude one file from git diff**
    
    git diff -- . ":(exclude)[filename]"

**Setup Git to Track Exisiing Repo**

    git remote add origin https://github.com/snphan/dafsaf.git
    git branch -M main
    git push -u origin main
    
**`Might need to add --allow-unrelated-histories flag when git pull`**
