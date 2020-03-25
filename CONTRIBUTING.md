
The contributions need to be done in individual branches. You can use your name or channel name as a branch name. Later please create MR to master and inform us to check and merge (or put assignees @magaras, @kazhang, @huirun). Please make sure you are able to compile the code without any problem before creating the MR.

If you are running on afs, one can use the 'setup.sh' to compile the code. Before commiting your changes, make sure to rrun the following command to avoid pushing the files created for compiling, and please do not push pdf file of the note.
```
make clean
```

Cloning the repository 
```
git clone ssh://git@gitlab.cern.ch:7999/atlas-physics-office/HDBS/ANA-HDBS-2019-04/ANA-HDBS-2019-04-INT1.git
```
Create your branch 
```
git checkout -b MyName
```
Check if there are modified files
```
git status
```
Add new or modified files for the next commit
```
git add file.tex ... (-A for all)
```
Commit my file in my local versioning
```
git commit -m "My commit message"
```
Push my commit on the remote repository (gitlab)
```
git push origin MyName
```
Ask for merging with master: "Merge request" -> "New merge request". 

Update local copy to master
```
git pull origin master
```

