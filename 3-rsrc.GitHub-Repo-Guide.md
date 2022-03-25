---
id: i3fjllklns6v3gbyeyabu4k
title: GitHub-Repo-Guide
desc: ''
updated: 1648014849430
created: 1648014849430
---

## Initialize
```bash
   git init
```

## Verify configuration file got created ".git"
  ```bash
    ls -la
  ```

## Rename the Master Branch
```bash
  git branch -m [ newBranchName ]
```

## Adds files to be tracked
```bash
  git add [ file name ]
  git add .
```

## Commit your changes
```bash
git commit -m "message"
```

## Get status of git directory
```bash
  git status
```

## Display commit log
```bash
git log
```

## Create a new branch

``` bash
git checkout -b [ branchName ]
```

## Switch to another branch
```bash
  git checkout [ branchName ]
```

## Merge branch changes to main
```
# Note: Ensure there are no pending changes to be pushed on either branch!
  # 1.Switch to branch
  # 2.Merge
  # 3.Solve conflicts / provide message
  # 4.Push Changes to updated branch
```

```bash
  git checkout main
  git merge [ branchName ]
  # solve conflicts in visual studio #
  git add .
  git commit -m "message about merge"
  git push
```

## Update a branch copy with main/master changes
```
# Note: Ensure there are no pending changes to be pushed on either branch!
  # 1.Switch to branch
  # 2.Merge
  # 3.Solve conflicts / provide message
  # 4.Push Changes to updated branch
```

```bash
  git checkout branchB
  git merge origin/main
  git push -or- git push origin branchB
```
