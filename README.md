# GitDemo
git项目演练


git init   --新建一个git本地仓库

git add <fileName>  --添加一个文件到缓存目录

git commit -m “tag”  --提交缓存到本地仓库

git reset hard fileName   --暂存区回到工作区，就是撤销了你之前的git add命令

git checkout  <filename>  --回退
  
git branch  <branchName>  --新建一个分支
  
git branch -d branchName  --删除本地分支
git push origin --delete Chapater6   --删除远程分支
git branch -a    --查看所有分支
  
git checkout branchName   --切换分支

git merge branchName   --合并分支

git log <-3>  --查看提交log

git log --oneline --graph  查看本地与远程的版本差异


git reset --hard commitid -- 回退到指令版本，可以通过git log 查看commitid

git remote add origin git@github.com:yourname/仓库名.git  --新增github仓库地址

git push -u origin master     --本地代码提交至远程仓库

git clone git@github.com:yourname/仓库名.git   --远程仓库代码下载本地


git diff master origin/master   比较本地和远程的差异


git fetch origin master:tmp
git diff tmp 
git merge tmp
    从远程获取最新的版本到本地的test分支上
   之后再进行比较合并
2. git pull：相当于是从远程获取最新版本并merge到本地

git文章：https://www.git-tower.com/learn/git/ebook/cn/command-line/introduction#start


 
