# Comprehensive Git Commands List

This repository contains a comprehensive list of Git commands for reference.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Working with Local Repositories](#working-with-local-repositories)
3. [Working with Remote Repositories](#working-with-remote-repositories)
4. [Branching and Merging](#branching-and-merging)
5. [Inspecting and Comparing](#inspecting-and-comparing)
6. [Troubleshooting](#troubleshooting)
7. [Advanced Commands](#advanced-commands)

## Getting Started

1. `git init`: Initialize a new Git repository. Example: `git init`
2. `git clone`: Clone a repository from an existing URL. Example: `git clone https://github.com/user/repo.git`
3. `git config`: Set author name and email address respectively to be used with your commits. Example: `git config --global user.name "John Doe"`
4. `git stash apply`: Restore the most recently stashed changes.
5. `git stash list`: List all stashed changesets.
6. `git stash drop`: Discard the most recently stashed changeset.



## Working with Local Repositories

1. `git add`: Add a file to the staging area. Example: `git add filename`
2. `git commit`: Record changes to the repository. Example: `git commit -m "Commit message"`
3. `git status`: Show the status of files in the repository.
4. `git diff`: Show changes between commits, commit and working tree, etc.
5. `git restore`: Discard changes in the working directory. Example: `git restore filename`
6. `git log`: List the version history for the current branch. Example: `git log`
7. `git branch`: List all the local branches in the current repository. Example: `git branch`
8. `git checkout`: Switch branches or restore working tree files. Example: `git checkout branch_name`
9. `git merge`: Join two or more development histories together. Example: `git merge branch_name`
10. `git rebase`: Reapply commits on top of another base tip. Example: `git rebase branch_name`

## Working with Remote Repositories

1. `git pull`: Fetch and merge changes on the remote server to your working directory. Example: `git pull origin main`
2. `git push`: Push local commits to a remote repository. Example: `git push origin main`
3. `git remote`: Manage set of tracked repositories. Example: `git remote -v`
4. `git fetch`: Download objects and refs from a remote repository. Example: `git fetch origin`
5. `git remote add`: Add a remote repository. Example: `git remote add origin https://github.com/user/repo.git`
6. `git remote remove`: Remove a remote repository. Example: `git remote remove origin`
7. `git remote rename`: Rename a remote repository. Example: `git remote rename origin new_name`
8. `git remote show`: Show information about a remote repository. Example: `git remote show origin`
9. `git remote prune`: Remove remote tracking branches that no longer exist on the remote. Example: `git remote prune origin`
10. `git remote set-url`: Change the URL of a remote repository. Example: `git remote set-url origin https://github.com/user/new_repo.git`
11. `git remote update`: Fetch updates from all remotes. Example: `git remote update`
12. `git push --tags`: Push all tags to the remote repository. Example: `git push --tags`
13. `git push --delete`: Delete a remote branch. Example: `git push --delete origin branch_name`
14. `git fetch --prune`: Fetch and remove any remote-tracking references that no longer exist on the remote. Example: `git fetch --prune`


## Branching and Merging

1. `git branch`: List all the local branches in the current repository. Example: `git branch`
2. `git checkout`: Switch branches or restore working tree files. Example: `git checkout branch_name`
3. `git merge`: Join two or more development histories together. Example: `git merge branch_name`
4. `git rebase`: Reapply commits on top of another base tip. Example: `git rebase branch_name`
5. `git branch -d`: Delete a branch. Example: `git branch -d branch_name`
6. `git branch -m`: Rename a branch. Example: `git branch -m new_branch_name`
7. `git branch -a`: List all branches (local and remote). Example: `git branch -a`
8. `git branch -r`: List all remote branches. Example: `git branch -r`
9. `git branch -vv`: Show local branches with tracking information. Example: `git branch -vv`
10. `git branch --merged`: List branches merged into the current branch. Example: `git branch --merged`
11. `git branch --no-merged`: List branches not merged into the current branch. Example: `git branch --no-merged`
12. `git merge --no-ff`: Perform a non-fast-forward merge. Example: `git merge --no-ff branch_name`
13. `git merge --abort`: Abort the current merge operation. Example: `git merge --abort`
14. `git rebase --continue`: Continue a rebase operation after resolving conflicts. Example: `git rebase --continue`
15. `git rebase --skip`: Skip the current commit during a rebase operation. Example: `git rebase --skip`
16. `git rebase --abort`: Abort the current rebase operation. Example: `git rebase --abort`


## Inspecting and Comparing

1. `git log`: List the version history for the current branch. Example: `git log`
2. `git blame`: Show what revision and author last modified each line of a file. Example: `git blame filename`
3. `git shortlog`: Summarize 'git log' output. Example: `git shortlog`
4. `git describe`: Give an object a human-readable name based on an available ref. Example: `git describe`
5. `git show`: Show various types of objects. Example: `git show commit_hash`
6. `git diff`: Show changes between commits, commit and working tree, etc. Example: `git diff commit_hash`
7. `git difftool`: Show changes using an external diff tool. Example: `git difftool commit_hash`
8. `git log --graph`: Show the commit history as a graph. Example: `git log --graph`
9. `git log --since`: Show the commit history since a specific date. Example: `git log --since="2022-01-01"`
10. `git log --author`: Show the commit history by a specific author. Example: `git log --author="John Doe"`
11. `git log --grep`: Show the commit history matching a specific pattern. Example: `git log --grep="bug fix"`
12. `git log --stat`: Show statistics about file modifications in each commit. Example: `git log --stat`
13. `git log --oneline`: Show a condensed one-line commit history. Example: `git log --oneline`
14. `git log --follow`: Show the history of a file, including renames. Example: `git log --follow filename`
15. `git show-branch`: Show branches and their commits. Example: `git show-branch`


## Troubleshooting

1. `git bisect`: Find the commit that introduced a bug by using binary search. Example: `git bisect start`
2. `git blame`: Show what revision and author last modified each line of a file. Example: `git blame filename`
3. `git revert`: Revert a previous commit by creating a new commit. Example: `git revert commit_hash`
4. `git reset`: Unstage changes or move the current branch to a specific commit. Example: `git reset HEAD filename`
5. `git cherry-pick`: Apply changes from a specific commit to the current branch. Example: `git cherry-pick commit_hash`
6. `git reflog`: Reference logs, a list of where your HEAD and branch references have been. Example: `git reflog`
7. `git clean`: Remove untracked files from the working directory. Example: `git clean -n`
8. `git stash`: Temporarily save changes that are not ready to be committed. Example: `git stash save "Work in progress"`
9. `git show-ref`: Show references (branches, tags, etc.) in a repository. Example: `git show-ref`
10. `git fsck`: Check the integrity of Git objects in the repository. Example: `git fsck`
11. `git remote update`: Fetch updates from all remotes. Example: `git remote update`
12. `git submodule`: Manage Git submodules within a repository. Example: `git submodule init`
13. `git archive`: Create a tar or zip archive of a Git repository. Example: `git archive --format=zip --output=archive.zip HEAD`
14. `git help`: Display help information about Git commands. Example: `git help commit`
15. `git stash drop`: Discard the most recently stashed changeset. Example: `git stash drop`



## Advanced Commands

1. `git reflog`: Reference logs, a list of where your HEAD and branch references have been. Example: `git reflog`
2. `git cherry`: Show the changes yet to be applied to the upstream branch. Example: `git cherry -v origin/main`
3. `git rebase -i`: Interactively rebase commits. Example: `git rebase -i HEAD~3`
4. `git filter-branch`: Rewrite branches to remove unwanted commits. Example: `git filter-branch --tree-filter 'rm -f filename' HEAD`
5. `git submodule`: Manage Git submodules within a repository. Example: `git submodule init`
6. `git rebase --onto`: Reapply commits onto a new base commit. Example: `git rebase --onto new_base_commit old_base_commit branch_name`
7. `git stash apply`: Apply a stashed changeset to the working directory. Example: `git stash apply stash@{2}`
8. `git bisect`: Automate the process of finding a faulty commit. Example: `git bisect start HEAD bad_commit`
9. `git worktree`: Manage multiple working trees associated with a single repository. Example: `git worktree add ../worktree1 branch_name`
10. `git blame --since`: Show who last modified each line of a file since a specific date. Example: `git blame --since="2022-01-01" filename`
11. `git notes`: Add or inspect object notes. Example: `git notes add -m "Note message" commit_hash`
12. `git rev-parse`: Parse a Git revision (SHA-1, branch name, etc.) into a full SHA-1. Example: `git rev-parse HEAD`
13. `git clean`: Remove untracked files from the working directory. Example: `git clean -n`
14. `git cherry-pick --abort`: Abort the cherry-pick operation. Example: `git cherry-pick --abort`
15. `git archive`: Create a tar or zip archive of a Git repository. Example: `git archive --format=zip --output=archive.zip HEAD`
16. `git rerere`: Reuse recorded resolution of conflicted merges. Example: `git rerere`
17. `git blame`: Show what revision and author last modified each line of a file. Example: `git blame filename`
18. `git submodules`: Manage Git submodules within a repository. Example: `git submodule init`
19. `git stash`: Temporarily save changes that are not ready to be committed. Example: `git stash save "Work in progress"`
20. `git bundle`: Move Git objects and references between repositories as a single file. Example: `git bundle create repo.bundle --all`





## Conclusion

This is not an exhaustive list of all Git commands, but it should cover most of the commands you'll need on a daily basis. Always remember to understand what a command does before you use it. Happy coding!
