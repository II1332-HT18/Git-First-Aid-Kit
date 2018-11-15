# Git-First-Aid-Kit
This is a guideline how you should use Git and Github to boost your productivity.

## First-time Setup
Before you can get your hands dirty, should you provide Git your username and email on GitHub.

```sh
# Set GitHub username and email
$ git config --global <username>
$ git config --global <email>
```
Now, you're ready to clone a repo to your computer!

```sh
# clone a repo from GitHub
$ git clone <repo>
# Enter Working Directory
$ cd <repo>
```

## Daily Development
A new day! Wohoo! Start by pull from **origin**
```sh
# check if there is any uncommitted file in **staging area**
$ git status                            #Github Desktop: simply check staging area
$ git pull origin <stable-branch>       #Github Desktop: fetch origin
$ git checkout -b <development-branch>  #Github Desktop: create new branch
DO YOUR WORK HERE
$ git add <filename>                    #Github Desktop: double-click filename to add to staging area
# git status makes sure that you commit what you really want to commit
$ git status                            #Github Desktop: simply check staging area
# Write something about this commit
$ git commit -m "commit message"        #Github Desktop: write in "summary"
$ git push origin development-branch    #Github Desktop: push origin
```

## Pull Request
Fantastic that you want to contribute to master! You do like follows:
1. On github.com, choose the branch you want to merge, click the button "New pull request"
2. Write something about what you have done
3. Write why you want to merge in description
4. Request reviews from brislov(Marcus), Dollf(Alpha), rlindsberg(Roderick) and nessnah198(RTOS-Johan)
