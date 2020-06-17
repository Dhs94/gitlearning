Git learning
1.git init	创建库(本地仓库初始化)
2.git add filename	将文件添加到暂存区
3.git commit -m "modify content"	提交更改到当前分支
4.git status	查看文件状态
5.git log --pretty=online	查看提交记录
6.git checkout --filename	丢弃工作区的修改（记得加 --，否则是切换分支命令）	
7.git reset --hard HEAD^	版本回退(HEAD当前版本，HEAD^上一个版本，HEAD^^上上版本)
8.git diff HEAD --filename	工作区和暂存区file的区别
9.git reset HEAD filename	撤销暂存区修改
10,git restore filename		撤销暂存区修改
11.git remote add origin path	关联远程库
12.git push -u origin master	push代码到远程库的master分支（第一次推送时加-u，把本地master和远程master关联起来）
13.git clone path	克隆远端代码
14.git checkout -b branchname	创建分支并切换到该分支
15.git branch		查看当前分支
16.git checkout branchname	切换分支
17.git branch -d branchname	删除分支
18.git merge brachname		合并分支
19.git merge --no-ff branchname		加上--no-ff参数就可以用普通模式合并，合并后的历史有分支，能看出来曾经做过合并
20.git stash	把当前工作现场“储藏”起来
21.git remote	查看远程库信息
22.git remote -v	查看远程库信息（更详细）
23.git pull	拉去最新代码
24.git checkout -b branchname origin/branchname		在本地创建和远程分支对应的分支，本地和远程分支的名称最好一致
25.git branch --set-upstream branchname orign/branchanme	建立本地分支和远程分支的关联
