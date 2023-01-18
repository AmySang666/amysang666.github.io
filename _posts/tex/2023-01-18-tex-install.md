---
layout: post
title:  "LaTeX安装与TeX studio配置——以windows11为例"
date:  2023-01-18 00:14:54
categories: LaTeX TeXstudio
tags: LaTeX TeXstudio
excerpt: 安装LaTeX，配置TeX studio，实现更方便的文档排版体验
mathjax: true
---

# TeX Live的下载与安装

在tug.org上，选择CTAN源，下载Tex Live的iso镜像。

![image](/img/tex_pic/tex1.png)

在https://ctan.org/mirrors/mirmon这个网站上，可以看到不同网站的拥堵状况。

下载TeX Live的iso镜像后，装载镜像（windows10操作类似），如下图所示管理员运行并安装。

![image](/img/tex_pic/tex2.png)

![image](/img/tex_pic/tex3.png)

![image](/img/tex_pic/tex4.png)

安装完成后，Abort按钮变灰，点击Close关闭即可。可以打开命令行，输入下面两行命令并回车，已经出现了版本号。

```
latex -v
xelatex -v
```

![image](/img/tex_pic/tex7.png)

# TeX studio的下载与安装

安装好TeX Live后，可以在TeX studio官网下载安装包。

![image](/img/tex_pic/tex5.png)

一路安装到底即可。

![image](/img/tex_pic/tex6.png)

在TeX studio的配置中，默认编译器设置为XeLaTeX。

![image](/img/tex_pic/tex8.png)

# 论文编译

英文版操作系统，编译中文需要安装中文字体。

[官方指南](https://www.tug.org/texlive/doc/texlive-en/texlive-en.html#tlportable)