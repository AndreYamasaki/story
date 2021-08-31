# story
using git commands in terminal

git status 
shows the current state of your Git working directory and staging area.

git add <file name>
Add file contents to the index
git add .
Add all files in directory

git commit
Record changes to the repository

git log
Show commit logs

git checkout <branch>
Switch branches or restore working tree files

git diff <commit>
Show changes between commits, commit and working tree, etc

git remote
Manage set of tracked repositories
git remote add <name> <url>
Add a remote branch to your GitHub repository

git push
Update remote refs along with associated objects
git push -u <remote> <branch>
Push your local repository to your remote repository

git rm
Remove files from the working tree and from the index
--cached
Use this option to unstage and remove paths only from the index. Working tree files, whether modified or not, will be left alone.
-r
Allow recursive removal when a leading directory name is given.

git branch
List, create, or delete branches
git branch <name>
The name of the branch to create or delete. The new branch name must pass all checks defined by git-check-ref-format[1]. Some of these checks may restrict the characters allowed in a branch name.

git-merge
Join two or more development histories together
