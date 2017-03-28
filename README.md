# karma
Kickoff meeting t1.txt
Agilemeeting notes
Moms 
Stories 
tasks

#linux command at first 
#!#bin/bash
mkdir
cd
cd/
whoami
vi
vim
touch t1.txt
touch t2.txt
vi t1.txt

t1.txt >> t2.txt
ls
ll
pwd
cat
touch
awk 
chksum
md5sum

#STARTING.....GITHUB ON MAC
init git 
Create the remote repository, and get the URL such as 

git@github.com:/youruser/somename.git or https://github.com/youruser/somename.git
https://github.com/prakash47chandra/karma.git
git@github.com:prakash47chandra/karma.git


If your local GIT repo is already set up, skips steps 2 and 3

Locally, at the root directory of your source, git init

Locally, add and commit what you want in your initial repo 
(for everything, 
git add . 
git commit -m 'initial commit comment'

to attach your remote repo with the name 'origin' (like cloning would do)
git remote add origin [URL From Step 1]

Execute git pull origin master to pull the remote branch so that they are in sync.
to push up your master branch (change master to something else for a different branch):
git push origin master

http://stackoverflow.com/questions/37937984/git-refusing-to-merge-unrelated-histories
git pull origin branchname --allow-unrelated-histories
