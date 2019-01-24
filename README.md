# GitDemo
git项目演练


git init   --新建一个git本地仓库

git add <fileName>  --添加一个文件到缓存目录

git commit -m “tag”  --提交缓存到本地仓库

git reset hard fileName   --暂存区回到工作区，就是撤销了你之前的git add命令

git checkout  <filename>  --回退
  
git branch  <branchName>  --新建一个分支
  
git checkout branchName   --切换分支

git merge branchName   --合并分支

git log <-3>  --查看提交log

git reset --hard commitid -- 回退到指令版本，可以通过git log 查看commitid

git remote add origin git@github.com:yourname/仓库名.git  --新增github仓库地址

git push -u origin master     --本地代码提交至远程仓库

git clone git@github.com:yourname/仓库名.git   --远程仓库代码下载本地



 
