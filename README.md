# Local Folder = Git
## Use this folder to hold programs that are 'work in process'

### Cheat Sheet
>git status // shows current status
>git init // from current folder, initializes folder as a local git repository
>git add readme.md (filename) // add a specified file to staging area, for next commit
>git add . // adds all files to staging area
git commit -m "message" // commits added files
git checkout -b new-branch-name // creates a new branch and copies data from main branch to new branch  
git checkout main // moves to main branch
git checkout new-branch-name // moves to new branch that was created
git merge main // will merge main branch into new_branch when current branch is new_branch
git merge new_branch // will merge new_branch into main branch when current branch is main
git push -u origin main // will push files found in branch main to origin main on GitHub. -u means 'save settings', next time all that is needed is git push and it will remember to push to 'origin main'.
git pull origin main // will pull files found in GitHub origin main to current local branch.