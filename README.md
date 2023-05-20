---
title: README
description: 
published: true
date: 2023-05-20T03:31:35.616Z
tags: 
editor: markdown
dateCreated: 2023-05-20T03:31:32.965Z
---

# 杭电导航

## 本文档目的

为了给杭电学生、老师更方便的杭电学校、生活，提供学校常见服务的资料整理，但是本文档并不存放时效类信息。

主要包含杭电学生学习生活大多需要的东西。暂定学习、图书馆、周边交通、教务系统、校园网络、阳光长跑、后勤（公寓、报修）、校车时刻表、学校地图、快递点等相关信息。

## 文档结构

### .github .git .gitignore

自动部署文件与版本控制文件，一般不动

### pages

文档正文保存位置，文件最大嵌套两级，所有文件文件名不能相同

### index.json

目录文件，确定目录的样式

```
{
    "id": "助手OAuth对接文档", // 所有目录的id不能重复
    "name": "助手OAuth对接文档", // 一级目录名字
    "open": false, // 是否默认展开
    "pages": [ // 二级目录
        {
             "name": "正文" // 二级目录名字，对应同名的md文件
        }
    ]
}
```

### README.md

项目说明文件