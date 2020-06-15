# Below are the list of Git command

### git config --global user.name "nadeemsiddiqui1980"
### git config --global user.email nadeem.s.siddiqui@hotmail.com

. git --version (Check Version)

. git init (For Initiating )

. git remote add origin https://github.com/fly2nadeem/Test001.git

. git status

. git add .FileName\ ( This is to add specific file in index)

. git add --all ( This is to add all file in index)

. git add . ( This is to add all file in index)

. git rm --cached Test1 -r(To remove file from from the index)

Example :
PS C:\Users\Samu\Desktop\Localrepo> git rm --cached Test1 -r                                       
rm 'Test1/Error.JPG'
rm 'Test1/Test-001.txt'

. git remote -v (This will show which remote repository is been added)

example :
PS C:\Users\Samu\Desktop\Localrepo> git remote -v                                                    
origin https://github.com/fly2nadeem?tab=projects (fetch)
origin  https://github.com/fly2nadeem?tab=projects (push)


. git remote remove (This will remove the remote repository which is been added)

example :

PS C:\Users\Samu\Desktop\Localrepo> git remote -v                                                  
origin  https://github.com/fly2nadeem?tab=projects (fetch)
origin  https://github.com/fly2nadeem?tab=projects (push)
PS C:\Users\Samu\Desktop\Localrepo> git remote remove origin                                      
 PS C:\Users\Samu\Desktop\Localrepo> git remote -v                                                  
 PS C:\Users\Samu\Desktop\Localrepo>  
 
. git commit -m "Initial Commit" (This is used to commit a file. -m stand for Message after which we have to provide message)

. git commit -m "Initial Commit"


. git log (This will provide you the list of log, like when it was committed, etc.)

. git pull origin master

. git push -u origin master

. git push -f origin master (This will push the local update to the remote repository. This is not recommended)

. git branch (This will give list of Branches)

*Note the you are in the branch which is in GREEN Colour*

. git branch branchname (This is to create new branch. Here we have created Branch mybranch)

. git branch mybranch

. git checkout branchname (This is used to swith the branch)

. git checkout mybranch

. git config --global --unset user.name - (To Log-Out from Github)
. git config --global --unset user.email - (To Log-Out from Github)
. git config --global --unset credential.helper - (To Log-Out from Github)
