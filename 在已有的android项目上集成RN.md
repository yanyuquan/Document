---
title:已有的项目集成ReactNative
tags: 新建,模板,小书匠
grammar_cjkRuby: true
---

目前facebook 的react-native 越来越火了，我认为它最大的优势在于比H5更流畅并且支持热发布。
结下来我们在已有的项目里集成RN。


# **添加reactNative**
1. 进入工程的根目录 npm init  生成package.json
   需要输入项目的名称，版本号，其他的可以回车跳过
  以下下是package.json 的内容：
   

``` stylus
{
  "name": "qdrn",
  "version": "1.0.0",
  "description": "learn RN ",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "yuquan_y",
  "license": "ISC"
}
```

2. 