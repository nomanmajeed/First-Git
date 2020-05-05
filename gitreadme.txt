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


 
