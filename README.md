# git-help-command


pwd <br/>
ls <br/>
clear <br/>
$ git config --global user.name "John Doe" <br/>
$ git config --global user.email johndoe@example.com <br/>
git init <br/>
git add . <br/> 
git commit -m  "This is our first commit" <br/>
git log <br/>
git log --author="buibup" <br/>
git status <br/>
git add second.txt <br/>
working copy > staging area > repository <br/>
git add .  //add all file <br/>
git diff <br/>
git diff --staged <br/>
git rm third.txt // remove third.txt file <br/>

git add home.txt >> git rm first.txt //rename <br/>
git mv second.txt pudding //rename <br/>
git mv pudding.txt LoveNotes/patty.txt //move to forder lovenotes and rename to patty.txt <br/>

git push origin master // push to github web site <br/>


//check diff file local and github <br/>
git fetch origin <br/> 
git diff master origin/master <br/>
//end

to update your local repository to the newest commit, execute <br/>
git pull <br/>




replace local changes <br/>
In case you did something wrong, which for sure never happens ;), you can replace local changes using the command <br/>
git checkout -- <filename><br/>
this replaces the changes in your working tree with the last content in HEAD. Changes already added to the index, as well as new files, will be kept.
<br>
If you instead want to drop all your local changes and commits, fetch the latest history from the server and point your local master branch at it like this<br>
git fetch origin<br>
git reset --hard origin/master<br>
