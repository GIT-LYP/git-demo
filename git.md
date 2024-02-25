## git 学习笔记

git 介绍 分布式版本控制工具

git安装 基于官网发布的最新版本2.31.1 安装讲解 

git命令 基于开发案例 详细讲解git 的常用名利命令 

git分支  分支的特性 分支创建 分支转换  分支合并 代码合并冲突解决

idea 集成git

===================**github**=================

创建远程库

代码推送Push

代码拉取 Pull

代码克隆 Clone

SSH免密登录

IDea集成GitHub

=====================**gitee**=================

创建远程库

Idea集成Gitee

码云连接github进行代码的复制和迁移



=====================**gitlab**===================

GitLab服务器搭建和部署 

Idea集成Gitlab

课程目标：五小时熟练掌握git  github gitlab  gitee 的使用 。

##### 1.git常用命令

1.设置用户签名（C:\Users\Administrator\.gitconfig）：为了区分不同操作者身份

 `git config --global user.name Imp`

 `git config --golobal user.email 2772578310@qq.com（邮箱随便设置）`



##### 2.用git管理目录 

**1.git init** 初始化本地库

**2.git status** 查看日志      

`On branch master` 当前分支

`nothing to commit, working tree clean` 

`No commits yet`  没有什么东西提交  

**3.ctrl+L** 清屏  

**4.常见的Linux 命令：

`**vim 文件名    i  键盘进入编辑    esc退出插入模式       yy是复制 p是粘贴****` 

`**：wq保存     ll查看文件         ll -a 查看隐藏目录   cat查看文件的内容 `

`tail -n 1 查看文件末尾的第一行**`

##### 4.添加暂存区

`1.git add hello.txt`

##### 5.提交本地库

`git commit -m "日志信息" 文件名`

`git reflog 引用日志信息 或者 gitlog 查看详细的日志信息`

##### 5.版本穿越：

`git reset --hard 5741c2e  用git reflog 查看想穿越的位置`  

##### 7.查看分支

`git branch -v       查看分支`

`git branch 名字      创建分支`

`git checkout 分支名  切换分支`

`git merge 分支名    把指定的分支  合并到当前分支上。`



`git remote -v    查看别名`   

`git remote add 别名 https地址    创建别名 可以推送也可以拉取`

##### 8.推送代码：

`git push 别名 分支名 git push git-demo master`

`拉取本地 git pull git-demo master`



`ssh-keygen -t rsa -C 2772578310@qq.com`
`测试语句这是我在github上的修改`







































