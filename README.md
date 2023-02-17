# Git-GitHub-Cheat-Sheet

# Basic Commands

- git init - Initialize Local Git Repository
- git add <file> - Add File(s) To Index
- git status - Check Status Of Working Tree
- git commit - Commit Changes In Index
- git push - Push To Remote Repository
- git pull - Pull Latest From Remote Repository
- git clone - Clone Repository Into A New Directory

# Git Other Commands

- touch <file> - add file
- git config  - -global [user.name](http://user.name) ‘crisaian’
- git config - -global [user.email](http://user.email) ‘crisaianvergara@gmail.com’
- git rm - -cached <file> - removed from stage to be committed
- git add *.html - add all html file to the stage to be committed
- git add . - add all files to the stage to be committed
- clear - clear the git bash

# More Git

- git log - check all commits
- git diff <filename> - check the difference
- git checkout <filename> - check the last version of the file when it was committed
- `git push -f origin master` - over ride when getting error on push
- git push - -all - push all branches

# Vim Editor when Committing

- press i to type
- Esc to escape
- Then :wq to go back to git bash
- last Enter
- Note: Better use this
- git commit -m ‘Change app.js’
- than using the Vim

# Ignore Other Files

- touch .gitignore - create this file
- then add the file you want to ignore

# Branches

- git branch login - create a branch
- git branch - check all branches
- git checkout login - change the current master to the branch login
- git merge login - merge the master and login branch

# Git to Github

- git remote - check repositories
- git remote remove <remote sample origin>
- git remote add origin <the file on git hub>
- git branch -M main
- git push -u origin main
- after that all steps you can just use
- git push
- and you are done

# Git Clone

- git clone <repository URL> - clone project

# Pull

- git pull - check when someone make a change
