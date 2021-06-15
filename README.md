# 2021/05/26 Git Collaboration O'reilly

- `git clone <URL>` : downloads the repository to current directory

## Branches

- `git branch <NAME>` : create branch
- `git branch -a` : list all branches
- `git branch -d <NAME>` : delete `<NAME>`
	- `git branch -D <NAME>` : force delete `<NAME>`
- `git switch <NAME>` : switch to `<NAME>`
	- `git checkout <NAME>` : "older" way to switch branches
- `git switch -c <NAME>` : create and switch to branch 1 command
	- `git checkout -b <NAME>` : same using checkout

## Pull Requests

- `git log --oneline --graph --all` : show you git history
- `git fetch --prune` : clean up your git history

## Conflicts

- `git rebase <BRANCH>` : e.g., `<MAIN>` will update current branch
