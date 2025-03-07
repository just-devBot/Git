# Git Commands

## Initialization

- `git init`: Initialize a new Git repository.

## Configuration

- `git config --global user.name "Your Name"`: Set the name that will be attached to your commits.
- `git config --global user.email "you@example.com"`: Set the email that will be attached to your commits.

## Basic Snapshotting

- `git add <file>`: Add a file to the staging area.
- `git commit -m "commit message"`: Commit the staged changes with a message.
- `git status`: Show the status of changes as untracked, modified, or staged.
- `git log`: Show the commit history.

## Branching and Merging

- `git branch`: List all branches in the repository.
- `git branch <branch-name>`: Create a new branch.
- `git checkout <branch-name>`: Switch to a specific branch.
- `git merge <branch-name>`: Merge a branch into the current branch.

## Remote Repositories

- `git remote add origin <url>`: Add a remote repository.
- `git push -u origin <branch-name>`: Push changes to the remote repository.
- `git pull`: Fetch and merge changes from the remote repository.

## Undoing Changes

- `git reset <file>`: Unstage a file.
- `git checkout -- <file>`: Discard changes in a file.
- `git revert <commit>`: Create a new commit that undoes the changes from a previous commit.

## Viewing History

- `git diff`: Show changes between commits, commit and working tree, etc.
- `git show <commit>`: Show various types of objects.

## Stashing

- `git stash`: Stash the changes in a dirty working directory away.
- `git stash apply`: Apply the stashed changes.

## Tagging

- `git tag <tag-name>`: Create a new tag.
- `git push origin <tag-name>`: Push a tag to the remote repository.

## Collaboration

- `git fetch`: Download objects and refs from another repository.
- `git rebase <branch>`: Reapply commits on top of another base tip.

## Advanced Commands

- `git cherry-pick <commit>`: Apply the changes introduced by some existing commits.
- `git bisect`: Use binary search to find the commit that introduced a bug.
- `git blame <file>`: Show what revision and author last modified each line of a file.

## Submodules

- `git submodule add <repository>`: Add a new submodule.
- `git submodule update --init --recursive`: Initialize, fetch and checkout submodules.

## Aliases

- `git config --global alias.<alias-name> <command>`: Create a shortcut for a Git command.

## Help

- `git help <command>`: Get help for a specific Git command.
