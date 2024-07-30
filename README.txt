## Git Initial Process

Step 01 -> IDE -> Terminal 
Step 02 -> git init 
Step 03 -> git add .
Step 04 -> git commit -m "upload" 
Step 05 -> git remote add origin https://github.com/Md-Soliman-Ali/example.git
Step 06 -> git push origin main

## Push Process

Step 01 -> git status
Step 02 -> git add .
Step 03 -> git status
Step 04 -> git commit -m "update"
Step 05 -> git push origin main

## Pull Process

Step 01 -> git pull origin main

## Git Username/email

Step 01 -> git config user.name
Step 02 -> git config user.email

## Switch Branch Process

Step 01 -> git fetch
Step 02 -> git branch -a
Step 03 -> git checkout branch_name

## Create New Branch Process

Step 01 -> git checkout -b develop
Step 02 -> git add .
Step 03 -> git commit -m "branch"
Step 04 -> git push origin develop

## Merge Process

Step 01 (main) -> git merge develop

## Github Contributor 

User One: Settings -> Collaborators -> Manage Access -> Add People (Github UserName) 
User Two: -> Email -> View invitation -> Accept invitation -> Code (HTTPS) -> Git Bash Here (git clone https://github.com/Md-Soliman-Ali/example.git) 

Step 01 -> git status 
Step 02 -> git add . 
Step 03 -> git commit -m "feature"  
Step 04 -> git push origin feature

## Pull Request Process

GitHub -> Repository -> Pull Request -> New pull request -> (base <- compare) -> Create pull request -> Create pull request -> Merge pull request -> Confirm merge
