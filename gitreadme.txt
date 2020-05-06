Readme file for Git Useage

Working Dir => Staging Dir => Git Repo Dir

1. Check Git Version => git --Version

2. Check git status => git status

3. To make a folder a git repo => git init

4. Initially after init call all files are untracked.

5. Type => git add .  to move it to staging dir for it to be committed finally

6. Recheck status for changes

7. To commit changes finally => git commit -m "Version X.X"

8. Befor committing do register yourself as super user
    => git config --global user.email "you@example.com"
    =>git config --global user.name "Name"

9. See who made changes respectively according to versions
    => git log

10. How to use Gitub, first make the repo on Github and through git bash on local machine folder
    make the origion of proj => git remote add origion SSH_URI

11. After commiting push it to github => git push -u origion master

12. For Pulling changes made through Github Web => git push origion master

13. For tracing yout changes in file before commiting => git diff file.ext
    For staged changes => git diff --staged file.ext 

14. For unstaging the changes
    File Specfic:
    => git reset file.ect
    => git checkout file.ext

    All Changes in multiple files
    => git checkout .
    
15. See all files => ls -la

16. CLone a git repo
    Folder inside Folder => git clone SSH_URI
    Repo insde Repo => git clone SSH_URI .

17. To make a Git Ignore file for those files that you don't want to commit
    => touch .gitignore (to initiate)
    => notepad .gitignore (to write rules on file)


##########################################################################################################################################

Branching in Git

1. See the branches:
    => git branch
 
2. Make new branch:
    => git branch branchname

3. Switch branch:
    => git checkout branchname

4. Merge the new branch to master
    => switch back to master
    => git merge branchname

5. Delete a branch from local system:
    => git branch -d branchname

6. Delete a branch from Github
    => git push origion --delete branchname
