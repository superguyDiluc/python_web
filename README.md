### 仓库地址

>   仓库地址：[https://gitee.com/dancefunk/demo](https://gitee.com/dancefunk/demo)

### 教程文档

>   [https://www.quickask.net/](https://www.quickask.net/)

### 成果递交资料

```
第一周：Web响应式布局项目
第二周：1.PythonWeb搭建 2.成果展示
```

```
最后一天递交的

递交资料的文件夹名称：年级-专业-PythonWeb实训-姓名
例子：2023-计算机科学与技术-PythonWeb实训-张三

1.每天写一篇实习日记（纸质+电子版word）

2.实训总结报告(纸质+电子版word)

3.实训的源码（2个压缩包）
   仓库地址：http://gitee.com
   1.PythonWeb(第三天的时候去弄) git仓库的名称：house
   2.Web响应式布局项目   git仓库的名称：spirit


   要求：
   1.这两个项目的源码要放到自己的git仓库上面，仓库链接放到PPT成果展示里面
   2.两个项目要运行好，然后压缩包，在最后一天递交的时候 一起提交过来

4.实训项目PPT
   1、响应式布局项目
      1.1 具体做法
      1.2 涉及到哪些技术
      1.3 搭建过程
      1.4 成果展示图片
      1.5 git仓库的链接地址

   2、PythonWeb二手房项目
      2.1 具体做法
      2.2 涉及到哪些技术
      2.3 搭建过程
      2.4 成果展示图片
      2.5 git仓库的链接地址
```

### Git版本控制工具

```
git 是可以多人协作 同时他可以对代码的提交做一个版本控制

注册gitee的账号: https://gitee.com

安装git工具：需要自己注意选择制定的安装路径

对git去进行一些基础的配置

win + R 打开 cmd 命令行窗口 设置
```

### 安装后的配置操作

```
检查 git 是否有安装成功
git --version

设置身份信息
git config --global user.name "昵称-英文"
git config --global user.email "填写邮箱地址"

远程操作需要重启安全认证
git config --global http.sslVerify true

免输入密码设置
git config --global credential.helper store

git忽略文件权限变化的检查
git config --global core.filemode false

git忽略所有文件的安全限制
git config --global --add safe.directory "*"

git处理换行符的设置
git config --global core.autocrlf true

查看自己写的对不对
git config list
```

### 克隆仓库

```
克隆别人的仓库和自己的仓库是一样的步骤
git clone 仓库的地址
https://gitee.com/dancefunk/demo.git

克隆仓库一定要去到你指定的文件夹中，右键点击菜单“open Git bash here”

对本地的仓库去进行操作
```

### 进入到仓库文件夹

>   cd demo


### 查看本地仓库是否有变化

>   git status
```
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
```

### 将文件添加到暂存区

>   git add [文件名|.代表所有文件]

```
git add .

git status

On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   demo1.html
```

### 提交操作

> git commit -m '备注的信息'

```
[master d547a8e] 首次提交文件
 1 file changed, 45 insertions(+), 56 deletions(-)
 rename "\350\256\262\344\271\211.md" => README.md (64%)
```

### 推送到远程的仓库

> git push 远程仓库的名字 分支的名字

```
界面上会弹框出来，让你输入账号和密码，就是gitee这个你注册账号密码
git push origin master

Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 20 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 2.03 KiB | 2.03 MiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Powered by GITEE.COM [1.1.5]
remote: Set trace flag 1547f6a6
To https://gitee.com/dancefunk/demo.git
   6c4339e..48fd1f6  master -> master
```

### 拉取最新的代码

>  git pull origin master

```
From https://gitee.com/dancefunk/demo
 * branch            master     -> FETCH_HEAD
Already up to date.
```

### 简写操作

```
git add . && git commit -m '备注信息' && git push origin master
```















