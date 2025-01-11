Hello!
Testing- second line, additional changes

Check status of changes to a repository
git status
View changes to files
git diff
Add a file's changes to be committed
git add <FILENAME>
To add all files changes
git add .
To commit (aka save) the changes you've added with a short message describing the changes
git commit -m "your commit message"


Add remote connections (usually origin for REMOTENAME)
git remote add <REMOTENAME> <URL>
Set a URL to a remote
git remote set-url <REMOTENAME> <URL>
Pull in changes
git pull <REMOTENAME> <BRANCHNAME>
View remote addresses
git remote -v
Push changes
git push <REMOTENAME> <BRANCH>