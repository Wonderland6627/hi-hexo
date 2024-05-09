---
title: Github + PicGo 搭建图床
date: 2024-05-08 23:38:50
tags:
    - Github
    - image host
categories:
    - 技术
top_img: https://cdn.jsdelivr.net/gh/Wonderland6627/cloudres/blog/07393c4437cc5e0cb7589e9194807fedd2cd0a3c.jpg
---

本教程将向您展示如何使用Github和PicGo搭建自己的图床（图片存储服务）。

## 创建Github仓库

1. 登录Github（[https://github.com/](https://github.com/)）。
2. 点击右上角的加号按钮，选择"New repository"。
3. 输入仓库名称，选择公开或私有，然后点击"Create repository"创建仓库。

## 安装PicGo

[PicGo](https://github.com/Molunerfinn/PicGo)是一个开源的图片上传工具，它可以方便地将图片上传到Github仓库。

1. 访问PicGo的Github仓库（[https://github.com/Molunerfinn/PicGo](https://github.com/Molunerfinn/PicGo)）。
2. 或使用镜像站下载，这里提供一个山东大学资源镜像站的PicGo链接（[https://mirrors.sdu.edu.cn/github-release/Molunerfinn_PicGo/v2.3.1/](https://mirrors.sdu.edu.cn/github-release/Molunerfinn_PicGo/v2.3.1/)）。
3. 根据您的操作系统，下载并安装适用于您的PicGo版本。（本教程以Windows版本为例）
4. 完成安装后，打开PicGo。

![](https://cdn.jsdelivr.net/gh/Wonderland6627/cloudres//blog/picgo-upload_main.png)

## 配置PicGo

在此步骤中，我们将配置PicGo以连接到您的Github仓库。

1. 打开PicGo，选择"图床设置"，找到Github选项。
2. 在"上传"选项卡中，选择"GitHub"作为图床类型。

![](https://cdn.jsdelivr.net/gh/Wonderland6627/cloudres//blog/pigo-github-settings.png)