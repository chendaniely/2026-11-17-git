# 2026-11-17-git

we will review 521 git basics and then go into branches

git branches: <https://ubc-dsci.github.io/reproducible-and-trustworthy-workflows-for-data-science/lectures/git-branches.html>

here's a command to help you look at the git history:

`git log --oneline --graph --decorate --all`

- `switch -c <name>`: create and move HEAD to the branch <name>

- `fetch --prune`: sync your work with the remote, and removes branches that were deleted from the remote

- `branch -d <name>`: deletes a branch that has been merged
- `branch -D <name>`: force delete a branch
