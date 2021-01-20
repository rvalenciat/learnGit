# learnGit
Repo to study Git

PASO 1 - My first Push. 
*  git status
*  git add README.md 
*  git status
*  git commit -m 'my first push'
*  git push origin main

PASO 2 - Create new branch from main
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
