---
title: Git GitHub node hexo环境搭建
date: 2017-07-09 15:02:47
tags:
---

## Git 初始化
## Github 密钥登录
## 安装hexo

<!-- more -->

## Git 初始化
1. git config --global user.email = xinxin_9921@163.com
	git config -- global user.name = baobaomao

## Github 密钥登录
ssh-keygen -t rsa -C "xinxin_9921@163.com"
登录GitHub，点击settings，选择SSH and GPG keys，填写title（随意），将~/.ssh/csser-github/csser-github.pub全部内容复制到key，保存即可
测试连接是否成功
ssh -T git@github.com
The authenticity of host 'github.com (192.30.255.112)' can't be established.
RSA key fingerprint is SHA256:nThbg6kXUpJWGl7E1IGOCspRomTxdCARLviKw6E5SY8.
Are you sure you want to continue connecting (yes/no)? yes
Warning: Permanently added 'github.com,192.30.255.112' (RSA) to the list of known hosts.
Hi baobaomao! You've successfully authenticated, but GitHub does not provide shell access.

## 安装hexo
1.安装node
2.npm install -g hexo
3.npm update
