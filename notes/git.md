# Git notes

## Core idead
- Repo: a folder git tracks. All the history lives in the hidden '.git' folder
- Commit: a saved snapshot of changes, with a message
- Branch: a separate line of work for the whole repo
- Merge: brings one branch's commits into another

## Everyday workflow
```
git status                      # what's changed?
git add <file>                  # stage it
git commit -m "message"         # save a snapshot
git push                        # upload to GitHub
```

## Branch workflow
```
git switch -c <branch-name>     # create + switch to a new branch
# edit, add, commit
git switch main
git merge <branch-name>
git push
git branch -d <branch-name>     # delete the branch once merged
```
