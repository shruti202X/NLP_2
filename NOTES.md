# Creting Local Repository

mkdir my_project

cd my_project

git init

git add .

git commit -m "message"

# Link local repository to the Remote

git remote add origin https://github.com/shruti202X/NLP_2.git

# Push code to the Remote Repository

git branch -M main

git push -u origin main

# Get code from remote repository

git pull origin main

Write commit message

Press Esc to ensure you're not in insert mode.

Type :wq (stands for write and quit).

Press Enter

# To untrack files

git reset <file_names>

# To undo last commit

git reset --soft HEAD~1

# to remove commits made to local but not to remote repository

git rebase -i <commit_hash>

change pick to drop

Esc

Enter