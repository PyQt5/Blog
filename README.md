# 博客项目

## 提交文章说明

1. 先 fork 本项目 或者 作为协作者加入本项目
2. 在 [source/_posts](source/_posts) 目录中编写文章
3. 文章格式见下面
4. 提交代码后发起合并请求

## 文章格式

1. 文件名必须为英文，且小于50字符
2. 内容开头格式如下
```
---
author: Irony
title: PyQtClient例子客户端
date: 2019-02-02 15:15:06
tags: 
 - Example
categories: 随笔
---

文章内容简介
<!-- more -->
```

## 字段说明

| 字段 | 说明 |
| :------:| :------: |
| author | 作者名字 |
| title | 中文标题 |
| date | 文章日期 |
| tags | 文章标签（可以多个） |
| categories | 文章分类（只能一个） |

## 注意

tags可以是多个，要注意格式对齐，比如：
```
tags:
 - Example
 - Tutorial
 - PyQt
```

目前常用的categories有：随笔，教程，例子