# Git Workshop

Disclaimer: Slightly opionionated

## Prerequisits

* ssh key
* git config --global user.name "Michael Mueller"
* git config --global user.email luca@mustermensch.de
* git config pull.rebase false

## Basics

* git init
* git clone
* git status
* git diff

## Aenderungen

* Staged?
* git add / git add -p
* git commit

## Commiting to git

* Gute Commits [1]

  * Separate subject from body with a blank line
  * Limit the subject line to 50 characters
  * Capitalize the subject line
  * Do not end the subject line with a period
  * Use the imperative mood in the subject line
  * Wrap the body at 72 characters
  * Use the body to explain what and why vs. how

## Remote

* git pull
* git push
* git push --force-with-lease

## GitHub

* Forking
* PR

## Workflow

* git checkout -b mybranch
* git fetch origin master
* git rebase origin/master mybranch
* git merge mybranch master
* Was sind Branches
* Rebase Workflow im Fork
* Merge wenn langlebig

## Advanced

# Tooling

* Github Desktop
* tig
* git

## End

* Learn Git Branching https://learngitbranching.js.org/
* Backspace Workshop https://github.com/b4ckspace/git-workshop
* Oh Shit, Git!?! https://ohshitgit.com/
* Notfall: https://github.com/louim/in-case-of-fire

[1] https://chris.beams.io/posts/git-commit/ 
