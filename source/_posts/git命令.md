---
title: python 学习中问题记录
date: 2018-03-20 14:13:06
tags: [git]
---

#此处记录一些在学习python中遇到的问题
*
*
*

##本地仓库提交到远程仓库
* 1、windows 右击打开git命令行
* 2、首次使用时配置
  * `git config --global user.name 'xxx' `# 配置github用户名
  * `git config --global user.email 'xxx' `# 配置github邮箱
  * `git config --list` # 查看配置结果
  * `cd F:\python` # 打开需要提交的文件夹
  * `git init` # 初始化git
  * `git add .` # 添加文件
  * `git commit -m "此处写注释"` # 提交代码注释
  * `git remote add origin https://github.com/zimengrao/PythonLearn.git`
  * `git push -u origin master` # 链接git远程仓库与本地仓库，等待输入用户名密码即可
* 3、修改代码提交
  * 命令行下，打开到项目根目录
  * git add . # 添加文件
  * git commit -m "此处写注释" # 提交代码注释
  * git push # 提交代码，等待输入用户名密码
 
##远程仓库克隆到本地
* 1、本地新建一个文件夹，在这个仓库下存放多个项目
* 2、`git clone https://github.com/zimengrao/PythonLearn.git` # PythonLearn项目名称
