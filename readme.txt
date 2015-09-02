README

GIT TEST
1... 2... 3... 4...

##checks the status of files in the git repository
git status

##stages file for the git repository
git add

##shows changes for files that are modified but not staged
git diff

##shows changes for files that have been modified and staged
git diff --cached

##commits the files staged and includes message (typed in editor after all the #)
git commit

##commits the files staged with the following message (type after m inside console)
git commit -m "message here"

##commits all files that have been modified without needing to be staged
git commit -a -m "message here"

##unstages file from the git repository (replace filename with name of file) Will delete the file from the computer
rm filename

##removes file from git repository (will not be tracked after the next commit)
git rm filename

##removes file from git repository without deleting it from the computer
git rm --cached README.txt

##renames file tracked by git (need to commit after rename)
git mv filename newfilename

##view commit history
git log

##view commit history and shows the differences
git log -p

##view recent commit history (n refers to how far back in the commit history) n is an integer
git log -n

##changes the last commit (results in only one commit)
git commit --amend

eg.
git commit -m "message"
git add newfile
git commit --amend

##unstages a staged file
git reset HEAD filename

##unmodify a modified file (changes are lost after reverting to original file)
git checkout -- filename


