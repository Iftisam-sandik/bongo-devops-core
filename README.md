# Bongo DevOps Core

This repository was created as part of my Git and GitHub assignment practice. The main goal of this project was to work with common Git workflows step by step and understand how they are used in real development work.

## What I practiced

- Initialized a Git repository and configured Git user information.
- Created and used `.gitignore` to keep `.env` out of version control.
- Created and switched between branches.
- Staged specific files and kept changes in separate commits.
- Connected the local repository with GitHub and pushed the `main` branch.
- Used `git log -p`, `git blame`, and `git show` to inspect commit history and track changes.
- Used `git stash` to save unfinished work temporarily and restore it later.
- Created multiple small commits on a feature branch and merged them into `main` as one clean commit using squash merge.
- Created and resolved a merge conflict manually.
- Used `git reflog` to recover a commit after a hard reset.

## Branches

The main branches used in this project are:

```text
main
feature/system-optimization
```

The `main` branch contains the final cleaned-up version of the work. The feature branch was used to practice isolated changes and squash merging.

## Some commands used

```bash
git init
git status
git add
git commit
git branch
git switch
git remote
git push
git log
git blame
git show
git stash
git merge --squash
git reflog
git reset --hard
```

## Repository files

Some of the files in this repository were created only for practicing specific Git tasks, such as configuration changes, stash workflow, merge conflicts, and recovery.

The `.env` file was intentionally kept out of Git using `.gitignore`.

## What I learned

This assignment helped me understand that Git is not only about saving code. Branching, commit history, stash, merge conflicts, and recovery tools are important when working on a shared project. I also got a better idea of why keeping commits clean and meaningful makes the project history easier to understand.

## Author

**Iftisam Sandik**  
GitHub: `Iftisam-sandik`
