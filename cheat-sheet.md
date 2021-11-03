# Git Cheat Sheet – Flavor Octocat

## Basic Commands

### Manipulating repositories

* ``git init``: Creates an empty Git repository on your local disk.
* ``git clone``: Creates a local copy of a remote Git repository. Requires HTTPS or SSH URL to clone from.
* ``git pull``: Updates a local copy of a remote Git repository.
* ``git checkout``: Switches to a different branch of a local Git repository. Can also be used to create new branches locally.
* ``git add``: Add a file within the directory structure of a local Git repository to version control.
* ``git commit``: Save currently untracked changes to a local Git repository.
* ``git push``: Updates a remote Git repository to match a local copy. Only works if no new commits have been made remotely on the same branch, else you must pull and merge/rebase first.


### Informative commands

* ``git status``: Display current untracked changes that can be committed.
* ``git log``: Display commits to a local Git repository in order of recency.
* ``git help``: Built-in help for Git commands - supply name of a particular command to learn about it.


## Advanced Commands

* `git blame` : Show what revision and author last modified each line of a file
* `git reflog` : Manage reflog information (equivalent to `git relog show HEAD`)
* `git effort` (from `git-extras` repository) : Show effort statistics on file(s) in repository 
* `git commit -m "Title of commit" -d "Description of commit"` : to specify a commit message and description without going to vim
* `aheadfork` : find GitHub forks that are ahead
* `git stash` : Stash the changes in a dirty working directory away

## Useful tools

- `GitKraken`:
  Git GUI for Windows, Mac & Linux! This intuitive Git GUI simplifies and streamlines Git processes.

  - Free version: 
    you can use the free version with public repositories but not with private ones.
  - Professional version:
    if you want to use the professional version, you can get it via GitHub education pack
    - https://education.github.com/students
    - https://education.github.com/teachers
    
  ![](images/gitkraken.png)

<br/><br/>

- `GitExplorer`
  - [GitExplorer.com](https://GitExplorer.com) is a very useful tool which helps novice git users cut through the clutter and find the right git commands without digging through the web.
  ![](images/gitexplorer.png)
  
  ## Pull requests and reviews
  
  - Create a pull request:
  1. a) After commiting your changes, go to "Pull Requests" -> "New pull request". Then, select the source as well as the target branch.
      b)Alternatively, you can `git push -u myfork mybranch` after the commit. Git will automatically generate the link to the corresponding pull request which you can copy and open in a browser of your choice. 
  2. Name the PR and fill out the template to shortly summarize what your PR contains / which changes you propose. You can also directly link to an open issue that is being solved by your changes (for this simply reference the issue via "#<number_of_the_issue>".
  3. Finally, click "Create pull request" to confirm.
  
  - Pull request templates:
  
  - Code review:

  - Close/merge pull request:
