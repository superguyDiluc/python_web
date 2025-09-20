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

1.每天写一篇日记
2.实训的源码
3.实训总结报告
4.PPT

实训项目的源码：
1.PythonWeb(第三天的时候去弄)
2.Web响应式布局项目

要求：
1.这两个项目的源码要放到自己的git仓库上面，仓库链接放到PPT成果展示里面
2.两个项目要运行好，然后压缩包，在最后一天递交的时候 一起提交过来
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















