# GitHub Tutorial

## How to add, commit, and push

1. First, we want to check the state of the repository: 
   - `$ git status`
   - You should see changes not added for commit in red.
2. Now add the changes (stage the changes) to your commit:
   - `$ git add <file>`
   - The following will add everything `$ git add -A`
3. Now check that it was properly added:
   - `$ git status`
   - You should see changes added to the commit in green.
4. Now commit your changes with a message:
   - `$ git commit -m "DESCRIPTIVE MESSAGE HERE"`
   - At this point, all your changes have been committed to a LOCAL branch
5. Push your changes to the remote version of your branch
   - `$ git push`

## How to branch

1. Go to GitHub repository, click on main in top left and create a new branch.