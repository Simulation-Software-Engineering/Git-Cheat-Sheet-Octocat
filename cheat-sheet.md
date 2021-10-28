# Git Cheat Sheet – Flavor Octocat

## Basic Commands

### Manipulating repositories

* git init: Creates an empty Git repository on your local disk.
* git clone: Creates a local copy of a remote Git repository. Requires HTTPS or SSH URL to clone from.
* git pull: Updates a local copy of a remote Git repository.
* git checkout: Switches to a different branch of a local Git repository. Can also be used to create new branches locally.
* git add: Add a file within the directory structure of a local Git repository to version control.
* git commit: Save currently untracked changes to a local Git repository.
* git push: Updates a remote Git repository to match a local copy. Only works if no new commits have been made remotely on the same branch, else you must pull and merge/rebase first.


### Informative commands

* git status: Display current untracked changes that can be committed.
* git log: Display commits to a local Git repository in order of recency.
* git help: Built-in help for Git commands - supply name of a particular command to learn about it.
