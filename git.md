## git 

git 介绍 分布式版本控制工具

git安装 基于官网发布的最新版本2.31.1 安装讲解 

git命令 基于开发案例 详细讲解git 的常用名利命令 

git分支  分支的特性 分支创建 分支转换  分支合并 代码合并冲突解决

idea 集成git

===================github=================

创建远程库

代码推送Push

代码拉取 Pull

代码克隆 Clone

SSH免密登录

IDea集成GitHub



=====================gitee=================

创建远程库

Idea集成Gitee

码云连接github进行代码的复制和迁移



=====================gitlab===================

GitLab服务器搭建和部署 

Idea集成Gitlab

课程目标：五小时熟练掌握git  github gitlab  gitee 的使用 。

### git常用命令

用户签名（C:\Users\Administrator\.gitconfig）区分不同操作者身份

 git config --global user.name Imp

git config --golobal user.email 2772578310@qq.com



##### 初始化本地库：你要用git管理目录 

1.git init 初始化本地库

2.git status 查看日志         on branch（分支） master 当前分支

No commits yet  没有什么东西提交  

3.ctrl+L 清屏  

4.vim hello.txt   i 键盘进入编辑 esc退出插入模式     yy是复制 p是粘贴 

  ：wq保存 ll查看   ll -a 查看隐藏目录 cat查看文件的内容 tail -n 1 查看文件末尾的第一行

##### 添加暂存区

1.git add hello.txt

##### 提交本地库

git commit -m "日志信息" 文件名

git reflog 引用日志信息 或者 gitlog 查看详细的日志信息

##### 版本穿越：

git reset --hard 5741c2e  用git reflog 查看想穿越的位置  

##### 查看分支

git branch -v 查看分支

git branch 名字   创建分支

git checkout 分支名    切换分支

git merge 分支名       吧指定的分支  合并到当前分支上。



git remote -v 查看别名

git remote add 别名 https地址  这个是创建别名 可以推送也可以拉取

##### 推送代码：

git push 别名 分支名 git push git-demo master

拉取本地 git pull git-demo master



ssh-keygen -t rsa -C 2772578310@qq.com







































