github脊梁命令
=
***
克隆远程仓库
>git clone git@github.com:你的Github用户名/for-fem.git  
ps：只克隆了master分支
***
分支管理（1）
>假设远程仓库中有2020mooc分支  
在当前分支下创建子分支2020mooc并切换到2020mooc分支   
git checkout -b 2020mooc  
将当前分支推送到远程，并在远程创建分支2020mooc   
git push -u origin 2020mooc  
***
分支管理（2）
>假设远程仓库中已有2020mooc分支  
git checkout -b 2020mooc origin/2020mooc     
如已有本地分支2020mooc，先删除本地分支2020mooc  
git branch -d 2020mooc  
再运行  
git checkout -b 2020mooc origin/2020mooc  
***
日常操作
>git pull    只下载当前分支  
git status   查看修改状态  
git add .    除忽略文件类型外，所有被修改的文件都提交到中转站  
git commit -m “Prepare for solidbeam branch”   实现提交  
git status   查看修改状态的提交情况  
git push     只推送当前分支  
***
分支切换
>git checkout 目标分支 # 将“目标分支” 切换为当前分支  
git branch -a          # 显示全部分支信息，带 \* 号的为当前分支  
git merge 被合并分支   # 将被合并分支，合并到当前分支
***