Basic Commands:
Initialize a repository:
git init

Clone a repository:
git clone <repository-url>

Check status of files:
git status

Add files to the staging area:
git add <file>
git add . (add all files)

Commit changes:
git commit -m "Commit message"

Branching & Merging:
Create a new branch:
git branch <branch-name>

List branches:
git branch

Switch to a branch:
git checkout <branch-name>
or (Git 2.23+): git switch <branch-name>

Create and switch to a new branch:
git checkout -b <branch-name>

Merge a branch:
git merge <branch-name>

Delete a branch:
git branch -d <branch-name>

Remote Repositories:
List remote repositories:
git remote -v

Add a remote repository:
git remote add <name> <repository-url>

Push changes to a remote repository:
git push <remote> <branch>

Pull changes from a remote repository:
git pull <remote> <branch>

Undoing Changes:
Revert changes in a file:
git checkout -- <file>

Unstage files (keep changes):
git reset <file>

Reset to a specific commit:
git reset --hard <commit-hash>

Viewing Changes:
View commit history:
git log

Show differences between commits:
git diff

Show changes in staged files:
git diff --staged

Stashing:
Stash changes:
git stash

Apply stashed changes:
git stash apply

List stashes:
git stash list

Tagging:
Create a tag:
git tag <tag-name>

List all tags:
git tag

Push tags to remote:
git push <remote> --tags

Miscellaneous:
Show commit details:
git show <commit-hash>

Create an archive of the repository:
git archive --format=zip --output=<file.zip> <branch-name>
