---
title: 多PC同步博客
date: 2018-02-18 22:00:20
tags:
   - Hexo
   - Github
---


## 环境安装

1.[Node.js安装](https://nodejs.org/en/)
2.[Git安装](https://gitforwindows.org/)

## Git配置

在命令行中输入

> $ git config --global user.name "username"
$ git config --global user.email "username@example.com"

## 设置SSH Keys

> ssh-keygen -t rsa -C "1064732243@qq.com"

完成后，会在用户主目录下生成.ssh目录，里面有`id_rsa`和`id_rsa.pub`两个文件，这两个就是SSH key密钥对，`id_rsa`是私钥，`id_rsa.pub`是公钥。打开文件中`id_rsa.pub`直接复制其内容：

![](http://ovvd7k5mv.bkt.clouddn.com/18-2-20/19481466.jpg)

在GitHub右上方点击头像，选择`Settings`，在右边的Personal settings侧边栏选择`SSH and GPG Keys`。接着选择SSH keys右边的`New SSH key`,然后粘贴key.

然后输入

> $ ssh -T git@github.com

## 安装Hexo

> npm install -g hexo

## 文件Copy

1._config.yml，theme/，source/，scaffolds/，package.json，.gitignore，需要copy。
2.git/，node_modules/，public/，.deploy_git/，db.json不需要。

## 组件安装

为了为了使用`hexo d`来部署到git上，需要安装:

> npm install hexo-deployer-git --save

