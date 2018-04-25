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
初始化： `git init`
克隆项目：`git clone`
#### 添加/删除文件
添加指定文件到暂缓区：`git add [file]`
添加所有文件到暂缓区：`git add .`
删除文件，并放入暂缓区：`git rm [file]`
#### 代码提交
提交至仓库：`git commit -m [*备注信息]`
