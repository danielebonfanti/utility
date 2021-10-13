# SOME USEFUL GIT COMMAND

## empty stash list

git stash clear

## undo last commit

git reset --hard HEAD~1
git reset --soft HEAD~1

## fetch all origins

git fetch --all

## add origin

git remote add *name* *remote_url*

## search branch by user

git for-each-ref --format=' %(authorname) %09 %(refname)' --sort=authorname
