---
title: android jenkins  配置
tags: jenkins
grammar_cjkRuby: true
---

将android-qding目录放到.jenkins/job 目录下，重启jenkins即可看到jenkins项目 。

![enter description here][1]

一、这个android jenkins项目可以动态的修改版本号已经app 的环境。
1.版本号的修改是通过修改gradle.properties
2.环境的修改是通过productFlavors 修改的。如何
![enter description here][2]


二、接下来说一下jerkins配置
1.配置下git或者svn
2.配置打包脚本（gradle）
![enter description here][3]
这里的task 可以根据android studio gradle标签查看以下如下图：
![enter description here][4]


  [1]: ./images/1513051856462.jpg
  [2]: ./images/1513052078712.jpg
  [3]: ./images/1513052485915.jpg
  [4]: ./images/1513052596334.jpg