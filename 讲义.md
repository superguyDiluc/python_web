git 是可以多人协作 同时他可以对代码的提交做一个版本控制


注册gitee的账号: https://gitee.com

安装git工具：需要自己注意选择制定的安装路径

对git去进行一些基础的配置

win + R 打开 cmd 命令行窗口 设置

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


克隆别人的仓库和自己的仓库是一样的步骤
git clone 仓库的地址
https://gitee.com/dancefunk/demo.git

克隆仓库一定要去到你指定的文件夹中，右键点击菜单“open Git bash here”

对本地的仓库去进行操作

进入到仓库文件夹
cd demo

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




















-----------------------------------------------------------------
python 学了一个学期 就是一些基础语法
mysql sql 增删查改

python-web web前端方面的内容
html + css + 

web方面的开发的

后端语言
python
java
php
go


开发岗位：
    WEB全栈开发： 
        WEB前端开发:
        WEB后端开发: java python go php nodejs



1/响应式项目(响应式界面设计) 重点

2/python-web 以搭建为主 能够运行起来 有成果展示
flask
mysql
前端

响应式布局：
html 超文本标记语言
css  层叠样式表
javascript web的脚本语言


margin-left : 左边距


动画3个大的概念：
    变换样式 transform
    过渡样式 transition 从很生硬变化的效果 变成平缓的效果
    自定义动画样式 animation

transition


transform