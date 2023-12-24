# Hello world

Maysha Khanom Moon
<br>
Maysha-Khanom-Moon


## some command

1. 'clear': cls
2. 'ls': dir, dir /B, dir /A, dir /A:H
3. git config --global user.name "username"
4. git config --global user.emain "useremail"
5. git config --get user.name
6. git config --get user.email
7. cd 'filepath'
8. cd ..
9. git remote -v
10. del .git\index.lock
11. git add filename
12. git add .
13. git status
14. git commit -m "msg"
15. git push origin main
<br>
push - upload local repo content to remote repo
<br>

### mkdir
mkdir dirName

### init Command
init - create existing folder to a new git repo
<br>

1. git init
2. git remote add origin <-link->
3. git remote -v (to verify remote)
4. git branch (to check branch)
5. git branch -M main (to rename branch 'main')
6. git push origin main

7. git push -u origin main
=> future a bar bar origin main jeno na likha lage, tai -u. Next time just git push likhlei hobe.


# work flow
=> GitHub repo --> clone --> change --> add --> commit --> push

## Git Branches
1. git branch (to check branch)
2. git branch -M main (to rename branch)
3. git checkout <-branch name-> (to navigate)
4. git checkout -b <-new branch name-> (to create new branch)
5. git branch -d <-branch name-> (to delete branch)

==> j branch er moddhe thakbo, oita delete korte parbo nah.

# Merging Code

1. Way 1:
    => git diff <-branch name-> (to compare commits, branches, files & more)
    => git merge <-branch name-> (to merge 2 branches)

2. Way 2:
    => Create a PR


# Pull Request
=> It lets you tell others about changes you've pushed to a branch in a repository on GitHub.


# Notes
[link](https://www.apnacollege.in/notes)


# Undoing Changes
<h2>Case 1: staged changes</h2>
    => git reset <-file name-> (for one file)
    => git reset (for all file)


<h2>Case 2: commited changes (for one commit)</h2>
    => git reset HEAD~1

<h2>Case 3: commited changes (for many commits) </h2>
    => git reset <-commit hash-> (change hash exist)
    => git reset --hard <-commit hash-> (all hash change delete)


# Fork
=> create a rough copy at own account