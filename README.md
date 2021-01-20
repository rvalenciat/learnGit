# learnGit
Repo to study Git

STEP 1 - My first Push. 
*  git status
*  git add README.md 
*  git status
*  git commit -m 'my first push'
*  git push origin main

STEP 2 - Create new branch from main
*  git checkout -b new-branch-from-main
*  git add README.md
*  git status
*  git commit -m 'my first push to new branch'
*  git push origin new-branch-from-main

PASO 3 - Sacar del versionamiento
*  Remove from the source the following text: 
' otro texto ' 
*  git log
Este comando muestra los commits con los hash
*  git reset --hard <hash>
Este comando resetea la rama a un commit anterior 

STEP 4 - Merge Request
*  Generar merge request en Github
*  Mergear nueva rama con main 
*  git checkout main
*  git pull origin main

STEP 5 - Merque Request with conflicts
*  Generar merge request en Github
*  Use git manual command from Github

STEP 6 - Remove branch (local)
*  git branch
*  git branch -D <branch name>

STEP 7 - Retrieve

STEP 8 - Rebase