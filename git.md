# Git

## One Time Setup

`git config --global user.name "Isabella DeBoer"`
`git config --global user.email "isabella@songdeboer.net"`

## Project Setup

`git init`

## 3 Step Repeating Commit Process
1. Make changes to code
2. Stage related changes
    * git add
3. Commit changes with a message
    * git commit -m "Message"

## Commands

* status -> tell me what files have been staged or committed
* add -> add a file to the stage
* rm --chached -> remove file from stage
* git commit -m "Present tense description of what happened"
* git log -> Enter to move down, q to quit
* git checkout -- filename -> discard changes

## Problems
* commit without -m -> Usse Esc :wq to quit Vim
* wrong message -> git commit --amend -m "New message"
* wrong commit -> git checkout COMMIT_ID