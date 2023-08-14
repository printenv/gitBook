## git init

## Set user info 
- git config --global user.name "name"
- git config --global user.email "me@abc.com"
- git config --global core.editor 'code --wait'

## Check user info
- git config --global user.name

## Unstage and restore the state
1. git restore --staged test.txt
2. git restore test.txt

## reset
### --soft
head only
### --mixed (default)
head and staged
### --hard
head, staged and working
### example
git reset --soft e668(previous commit id)


## revert
reset delete commit. revert reset a commit by adding another commit.
### example
git revert --no-edit c398 

master test
sub2 branch test