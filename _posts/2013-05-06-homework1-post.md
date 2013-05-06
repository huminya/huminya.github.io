---
layout: post
title: "1.如何安装git和github"
description: "如何安装git和github"
category: homework
tags: [git, github, installation]
---
{% include JB/setup %}

# 我的作业20130505：1.如何安装git和github
## windows系统下安装git和github的步骤：
1. 安装GitHubSetup.exe，按照默认配置一步步安装即可；
2. 申请github账号，地址https://github.com/
3. 在GitHub帐户xxx页面下，创建名为new-project的新Repository，页面地址为https://github.com/new
建议在github新建一个yourname.github.io库
4. 在本地新建一个目录，目录名建议为yourname.github.io
5. 也可以克隆一个已有的项目到本地目录，命令为git clone http://website
6. 在本地cmd命令下，删除原有的权限 git remote rm origin；可以先用git remote查询权限；
7. 添加origin权限，命令 git remote add origin http://website
8. 提交git push -u origin master，输入用户名（邮箱也可以）和密码
9. 刷新页面，可以看到更新文件
10. 访问yourname.github.io，即可看到编译成功的页面

### 创建于 2013-5-7，0：09
