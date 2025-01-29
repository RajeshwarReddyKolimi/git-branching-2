# Git branching and rebasing

## Steps followed

- Created a new repository.
- Renamed master branch to main branch
- Added project.txt file.
- Staged and committed.
- Created 2 branches featureA, featureB.
- Checked to featureA, made some changes to project.txt, staged and committed.
- Checked to featureB, made some other changes to project.txt, staged and committed.
- Now in featureB, rebased featureB by `git rebase featureA`.
- There are conflicts and resolved them using git status and mergetool.
- Merge featureA into featureB by `git merge featureA`. Since already resolved conflicts while rebasing, no conflicts will be there now.
- Deleted featureA branch by `git branch -d featureA`.
- Merged featureB into main and pushed to remote repository.
