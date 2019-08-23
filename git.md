# Git

## One time setup 

'git config --global user.name "Noah Kivett"'
'git config --global user.email "nkiv33@gmail.com"' 

## Project setup

'git init'
'touch .gitignore'
Add '*.class' to the git .gitignore
file and save it.
'git add .'
'git commit -m "Initial commit"'

## 3 Steps Repeating Commit Process

1. Make Changes to code
    * git add
2. Stage related changes
3. Commit Changes with a message

## Commands 

* status -> Tell me what files have been staged or commited
* add -> add a file to the stage
* rm --cached -> remove file from stage
* git commit -m "Present tense description fo what changed"
* git log -> Enter to move down, q to quit
* git checkout -- filename -> discard changes


## Problems
* commit without -m  -> use Esc :wq to quit Vim
* wrong message -> git commit --amend -m "new message here"
* wroing commit -> git checkout COMMIT_ID