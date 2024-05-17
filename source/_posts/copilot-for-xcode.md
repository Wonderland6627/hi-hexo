---
title: 在XCode中使用Copilot
date: 2024-05-17 14:06:14
tags:
    - iOS
    - XCode
    - copilot
    - swift
categories:
    - 技术
    - iOS
top_img: https://cdn.jsdelivr.net/gh/Wonderland6627/cloudres/blog/07393c4437cc5e0cb7589e9194807fedd2cd0a3c.jpg
---

## 如何在XCode中使用Copilot辅助编程

### 安装 Copilot for XCode 插件
> https://github.com/intitni/CopilotForXcode

方法一：按照readme中，通过HomeBrew安装
```
brew install --cask copilot-for-xcode
```

方法二：直接下载Release安装包
> https://github.com/intitni/CopilotForXcode/releases/tag/0.33.0

安装成功后在启动台中搜索到即为安装成功

![](https://cdn.jsdelivr.net/gh/Wonderland6627/cloudres/blog/xcodecopilot/screenshot-20240517-142238.png)

### 开启插件扩展权限

进入Mac设置页的 隐私与安全性->扩展 

![](https://cdn.jsdelivr.net/gh/Wonderland6627/cloudres/blog/xcodecopilot/screenshot-20240517-142546.png)

打开所有关于Copilot for XCode的权限

![](https://cdn.jsdelivr.net/gh/Wonderland6627/cloudres/blog/xcodecopilot/screenshot-20240517-142629.png)

![](https://cdn.jsdelivr.net/gh/Wonderland6627/cloudres/blog/xcodecopilot/screenshot-20240517-142702.png)

![](https://cdn.jsdelivr.net/gh/Wonderland6627/cloudres/blog/xcodecopilot/screenshot-20240517-142715.png)

### 配置Copilot

打开 Copilot for XCode，进入Service页，可以看到左侧有很多类型的Copilot，不过GitHub Copilot是收费的，所以我们尝试使用免费的Codeium。

进入Codeium主页，注册账号并登陆
> https://codeium.com/

回到 Copilot for XCode，进入Service页，选择Codeium，点击Install，等待安装完成。

![](https://cdn.jsdelivr.net/gh/Wonderland6627/cloudres/blog/xcodecopilot/screenshot-20240517-110140.png)

点击Sign in，会跳转到Codeium网站，将Codeium网站中提供的key复制粘贴到 Copilot for XCode 中。

进入到 Feature 页，将 Feature provider 改为Codeium即可在XCode中体验Copilot啦。

![](https://cdn.jsdelivr.net/gh/Wonderland6627/cloudres/blog/xcodecopilot/screenshot-20240517-110242.png)

效果如下：

![](https://cdn.jsdelivr.net/gh/Wonderland6627/cloudres/blog/xcodecopilot/screenshot-20240517-155913.png)