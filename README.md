# Git & GitHub Advanced Workflow Lab

## Overview

This project demonstrates advanced Git and GitHub workflows used in real-world software development and DevOps environments.

The objective was to gain hands-on experience with:

* Pull Requests
* Git Reset
* Git Revert
* Git Stash
* Git Cherry-Pick
* Git Rebase
* Conflict Resolution

---

## Skills Covered

* Git Branching
* Pull Requests
* Version Control
* Commit Management
* Reset & Revert
* Stashing
* Cherry-Picking
* Rebasing
* Merge Conflict Resolution
* GitHub Collaboration

---

## Project Structure

```text
git-github-advanced-workflow-lab
├── screenshots
├── tasks
├── solution.md
└── README.md
```

---

# Task 1: Pull Request Workflow

## Project Structure

![Project Structure](screenshots/01_project_structure_created.png)

## Feature Branch Created and Pushed

![Feature Branch](screenshots/02_feature_branch_created_and_commited_pushed.png)

## Compare Pull Request

![Compare Pull Request](screenshots/Compare_Pull.png)

## Create Pull Request

![Create Pull Request](screenshots/Create_pull.png)

## Pull Request Merged

![PR Merged](screenshots/04_pull_request_merged.png)

## Repository After Merge

![Repository After Merge](screenshots/github_after_pr_merged.png)

---

# Task 2: Reset & Revert

## Reset Demo File Created

![Reset Demo](screenshots/06_reset_demo_file_created.png)

## Bad Commit Created

![Bad Commit](screenshots/07_bad_commit_created.png)

## Soft Reset

![Soft Reset](screenshots/08_soft_reset.png)

## Mixed Reset

![Mixed Reset](screenshots/09_mixed_reset.png)

## Hard Reset

![Hard Reset](screenshots/10_hard_reset.png)

## Git Revert

![Git Revert](screenshots/11_git_revert.png)

---

# Task 3: Git Stash

## Stash Demo File

![Stash Demo](screenshots/12_stash_demo_file_created.png)

## Uncommitted Changes

![Uncommitted Changes](screenshots/13_uncommitted_changes.png)

## Git Stash

![Git Stash](screenshots/14_git_stash_created.png)

## Hotfix Branch

![Hotfix Branch](screenshots/15_hotfix_branch_created.png)

## Stash Pop

![Stash Pop](screenshots/16_stash_pop.png)

## Stash Apply

![Stash Apply](screenshots/17_stash_apply.png)

## Stash Cleanup

![Stash Cleanup](screenshots/18_stash_cleanup.png)

---

# Task 4: Cherry-Picking

## Cherry-Pick Demo File

![Cherry Pick Demo](screenshots/19_cherry_pick_demo_file_created.png)

## Bug Fix Commit

![Bug Fix Commit](screenshots/20_bugfix_commit_created.png)

## Before Cherry-Pick

![Before Cherry Pick](screenshots/21_before_cherry_pick.png)

## Cherry-Pick Applied and Verified

![Cherry Pick Applied](screenshots/22_cherry_pick_applied_verified.png)

---

# Task 5: Rebasing

## Rebase Demo File

![Rebase Demo](screenshots/24_rebase_demo_file_created.png)

## Feature Branch Before Rebase

![Feature Branch Before Rebase](screenshots/25_feature_branch_before_rebase.png)

## Main Branch New Commit

![Main Branch Update](screenshots/26_main_branch_new_commit.png)

## Before Rebase History

![Before Rebase History](screenshots/27_before_rebase_history.png)

## Rebase Conflict Resolution

![Conflict Resolution](screenshots/28_rebase_conflict_resolution.png)

## Rebase Completed

![Rebase Completed](screenshots/29_rebase_completed.png)

## Rebase File Verified

![Rebase Verified](screenshots/30_rebase_file_verified.png)

---

# Key Learnings

### Pull Requests

* Collaborate safely using feature branches.
* Review code before merging.
* Maintain structured development workflows.

### Reset & Revert

* Reset rewrites history.
* Revert safely undoes changes while preserving history.

### Git Stash

* Save incomplete work temporarily.
* Switch contexts without creating unnecessary commits.

### Cherry-Picking

* Apply specific commits across branches.
* Useful for bug fixes and hotfixes.

### Rebasing

* Keep commit history clean.
* Avoid unnecessary merge commits.
* Improve project readability.

---

# Commands Practiced

```bash
git checkout -b <branch>

git add .

git commit -m "message"

git push origin <branch>

git reset --soft HEAD~1

git reset --mixed HEAD~1

git reset --hard HEAD~1

git revert HEAD

git stash

git stash pop

git stash apply

git cherry-pick <commit-id>

git rebase main
```

---

# Real-World Applications

* Team Collaboration
* Code Reviews
* Bug Fix Management
* Hotfix Workflows
* CI/CD Development
* DevOps Practices
* Production Issue Resolution

---

# Author

**Sriram Ganesh**

Completed as part of the **90 Days of DevOps** challenge.
