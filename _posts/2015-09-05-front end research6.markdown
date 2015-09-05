---
layout: post
title:  "前端技术研究6-Jekyll"
date:   2015-09-05 08:19:44
categories: jekyll update
---

Jekyll（发音/'dʒiːk əl/）是一个静态站点生成器，它会根据网页源码生成静态文件。它提供了模板、变量、插件等功能，所以实际上可以用来编写整个网站。

参考教程：

* [搭建一个免费的，无限流量的Blog----github Pages和Jekyll入门](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)
* [Jekyll • 简单的博客、静态网站工具](http://jekyll.bootcss.com/)
* [[原]通过GitHub Pages建立个人站点（详细步骤）](http://www.cnblogs.com/purediy/archive/2013/03/07/2948892.html)


可以使用Jekyll直接编写网页后上传，也可以安装ruby、jekyll后先在本地预览，然后再上传。  
安装jekyll本地预览环境 可以使用the GitHub Pages Gem 通过gem install github-pages进行安装  
gem命令必须得先安装ruby RubyGems是一个方便而强大的Ruby程序包管理器( package manager),类似RedHat的RPM.
ruby安装可以下载rubyinstaller-2.2.2-x64、DevKit后安装  
  http://rubyinstaller.org/downloads/  
 安装完成后打开解压后的DevKit压缩包中的msys.bat 输入以下命令  
  gem install github-pages  
 则jekyll本地预览集成环境安装成功  
 创建blog  
  ~$ gem install jekyll  
  ~ $ jekyll new my-awesome-site  
  ~ $ cd my-awesome-site  
  ~/my-awesome-site $ jekyll serve  
 \# => Now browse to http://localhost:4000  




