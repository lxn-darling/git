this is a new test for git;
先cd 到一个目录下然后将这个目录作为一个git 仓库
1. 初始化一个 git仓库 git init
3.git commit -m "提交说明"  提交文件到仓库
2.git add filename 添加文件到git仓库
4.git log 查看commit记录
5.git diff "filename" 查看文件变化
6.git reflog 记录每一次的命令 
7.git reset --hard "commit_id" 将当前版本回退到指定的版本
8. git checkout --filename 撤销文件的全部修改
9.git rm filename 从版本库中删除文件 如果误删了 任然可以不用git checkout来撤销删除
10.git push -u origin master 将本地库的所有文件推送到远程库当中去
11.git branch 查看分支
12. git branch <name> 创建分支
13. git checkout <name> 切换分支
14. git checkout -b <name> 创建+切换分支