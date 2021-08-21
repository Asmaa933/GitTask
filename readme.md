
# Git Task

Requirments

- [x] Start a new repo locally. 
- [x] Make sure to rename your main branch from "master" to "main"
- [x] Create a repo on your Github account. 
- [x] Add commits to your new project using best practices in commits/PRs. 
- [x] Use ".gitignore", "Readme", "PR template" files to ease the project use for your team. 
- [ ] Get two of your mates to approve your PRs.

## Git Commands

```
git init >> Creates a new Git repository
git status >> Displays the state of the working directory and the staging area
git log >> shows a list of all the commits made to a repository
git config --global init.defaultBranch main >> Changes git init default branch name

git remote add origin https://github.com/Asmaa933/GitTask.git >> links an existing project to a Git Remote
git remote -v >> Shows URLs of remote repositories 

git push -u origin main >> Pushes commits to a remote main

git checkout -b feature/readme >> Creates new branch(feature/readme) and switch to it
git checkout main >> Switches to main branch
git branch -d feature/readme >> Deletes local branch(feature/readme)
git branch >> Displays branches list

git add . >> Adds all file to staged Area 
git commit -m "Add readme file" >> Saves changes to the local repository
git push --set-upstream origin feature/readme >> Pushes feature/readme branch

git pull >> Updates the local version of a repository from a remote
git push >> Uploads local repository content to a remote repository

```

## Screenshots

<div>
<img src="https://user-images.githubusercontent.com/44899782/130331382-2a3e7bdd-6d77-49d4-9be2-7de73edef617.png">
</div>
