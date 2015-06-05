git status 
git add file
git commit -m"information"
git log :look history
git reset --hard (version版本号)HEAD^(1-100)
git reflog :every command
git checkout --file ：撤销工作(已经commit)区修改
git reset HEAD file :撤销暂存区修改(just add)
git push origin master :推送远程库
要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；

关联后，使用命令git push -u origin master第一次推送master分支的所有内容；

此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；

Git is free software.
now is 2015/5/31 23:32
today is 2015.6.5  18:04
