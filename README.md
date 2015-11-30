# git-help-command

# command

- pwd 
- ls 
- clear 
- git config --global user.name "John Doe" 
- git config --global user.email johndoe@example.com 
- git init 
- git add . 
- git commit -m  "This is our first commit" 
- git log 
- git log --author="buibup" 
- git status 
- git add second.txt 

working copy > staging area > repository
--------------
**add all file**
- git add .  


**diff**
- git diff 
- git diff --staged 


**remove third.txt file**
- git rm third.txt 

**rename**
- git add home.txt 
- git rm first.txt
- git mv second.txt pudding.txt


**move**
- git mv second.txt pudding.txt
  move to forder lovenotes and rename to patty.txt
- git mv pudding.txt LoveNotes/patty.txt 

**push to github web site**
- git push origin master  


**check diff file local and github**
- git fetch origin 
- git diff master origin/master 


**to update your local repository to the newest commit, execute** 
- git pull <br/>

replace local changes 
============
**In case you did something wrong, which for sure never happens ;), you can replace local changes using the command <br/>**
- git checkout -- <filename>
**this replaces the changes in your working tree with the last content in HEAD. Changes already added to the index, as well as new files, will be kept.**

**If you instead want to drop all your local changes and commits, fetch the latest history from the server and point your local master branch at it like this**
- git fetch origin<br>
- git reset --hard origin/master<br>
