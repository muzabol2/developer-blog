---
layout: post
title:  "Git commands"
permalink: "/git"
---

[git official documentation][gitDocPage]{:target="\_blank"} \
[git cheat sheet][gitCheatSheet]{:target="\_blank"}

List of GIT commands that I use a lot:

GIT Command  | Description
------------- | -------------
git init | initialize an existing directory as a Git repository
git clone *urlPath* | retrieve an entire repository from a hosted location via URL
git status  | show modified files in working directory, staged for your next commit
git add .  | add all files as they look now to your next commit (stage) 
git commit -m "*description*" | commit your staged content as a new commit snapshot
git pull  | fetch and merge any commits from the tracking remote branch
git push  | transmit local branch commits to the remote repository branch
git push -u origin *branchName* | if your branch is newly created, you need to upload the branch
git merge | merge a remote branch into your current to bring it up to date
git log | show the commit history for the currently active branch
git diff  | diff of what is changed but not staged
git stash  | save modified and staged changes
git stash list | list stack-order of stashed file changes
git stash pop | write working from top of stash stack
git branch | list your branches. a * will appear next to the currently used
git branch -d *branchName* | remove branch
git switch -c *branchName*  | crate new branch or *git checkout -b $BranchName*
git switch *branchName*  | switch to another branch
git switch - | switch to priev branch


[gitDocPage]: https://git-scm.com/docs/git
[gitCheatSheet]: https://education.github.com/git-cheat-sheet-education.pdf