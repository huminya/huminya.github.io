---
layout: post
title: "3，如何提交代码到github上？"
description: "如何提交代码到github上"
category: homework
tags: [commit code github]
---
{% include JB/setup %}

# 我的作业20130505：3，如何提交代码到github上？
## 3，如何提交代码到github上？
首次提交：
1. 在本地关联目录中，修改相关文件；
2. 在cmd命令行中，进入关联目录，执行git init；
3. 执行>git add [目录].（此处表示添加当前目录的所有文件，可以指定目录、文件），执行后将显示本次更新的文件信息；
4. 提交并添加注释（加注释是好习惯），执行>git commit -m "注释"
5. 关联本地和服务器：执行>git remote add origin https://github.com/yourname/xxx.git
6. push提交，执行>git push -u origin master
7. 稍等片刻，刷新blog地址（如yourname.github.io)，即可看到成果了。

再次提交：
除了不需要步骤5外，重复以上步骤即可；

### 创建于 2013-5-7 21:01