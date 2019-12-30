---
slug: 'learning-git'
title: 'learning-git'
linktitle: 'learning-git'
summary: ''
authors: ''
tags: []
categories: []
date: '2019-07-08'
lastmod: '2019-07-08T00:08:26+08:00'
featured: false
draft: false
toc: true
type: docs

menu:
  git:
    parent: ./
    weight: 2

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
---



![logo](/DATA/Lab/use-git/images/logo.png)





# Terminologys







## 01课程综述

版本管理理的演变

#### VCS 出现前

- 用目录拷贝区别不同版本
- 公共文件容易被覆盖
- 成员沟通成本很高,代码集成效率低下



#### 集中式 VCS

- 有集中的版本管理服务器
- 具备文文件版本管理和分支管理能力
- 集成效率有明显地提高
- 客户端必须时刻和服务器相连



#### 分布式 VCS

- 服务端和客户端都有完整的版本库
- 脱离服务端,客户端照样可以管理版本
- 查看历史和版本比较等多数操作,都不不需要访问服务器,比比集中式 VCS 更能提高版本管理效率





## 02安装Git

https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

```
$ git --version
```







# Basic Commands



