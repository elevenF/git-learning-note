# git快速上手
* 百度前端学院 mvvm学院 第一课笔记
* git快速上手指南
## git配置
配置个人用户名和邮箱信息
    
```
$ git config --global user.name 'Your userName'
$ git config --global user.email 'Your Email'
```

检查配置信息：`git config --list` || `git config <key>`来检查git的某一项配置

## git基础
#### 新建代码库
初始化： `git init`<br />
克隆项目：`git clone`
#### 添加/删除文件
添加指定文件到暂缓区：`git add [file]`<br />
添加所有文件到暂缓区：`git add .`<br />
删除文件，并放入暂缓区：`git rm [file]`
#### 代码提交
提交至仓库：`git commit -m [*备注信息]`
#### 分支管理
列出所有分支： 本地 `git branch` || 远程 `git branch -r`<br />
新建分支：`git branch [branchName]`<br />
新建并切换当前分支：`git checkout -b [branchName]`<br />
删除分支：`git branch -d [branchName]`<br />
删除远程分支：`git push origin --delete [branchName]`<br />
合并分支(指定分支到当前分支)：`git merge [branch]`
#### 查看信息
查看变更：`git status`<br />
查看历史版本：`git log`<br />
显示差异：`git diff`<br />
查看元数据与提交变化：`git show [commit]`<br />
显示最近几次提交：`git reflog`
#### 远端同步
拉取远端变化：`git pull`<br />
上传至远端：`git push`<br />
显示远端仓库：`git remote -v`
