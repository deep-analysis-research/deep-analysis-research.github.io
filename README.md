# 团队主页

这是团队主页的仓库，持续记录团队的成果，包括但不限于技术博客、研究成果、talk分享、Demo展示。我们致力于分享在技术上的所见所闻、所思所想，也热衷欢迎不同思想、见解的碰撞。

欢迎访问我们的主页：[团队主页](https://deep-analysis-research.github.io/)

# 仓库介绍和维护

本仓库继承了[Hype](https://github.com/poole/hyde)的主要结构，进行了定制化调整，目前分为：主页、博客、论文、Demo四个板块

- 主页：highlight的内容展示
- 博客：团队内同学对不同topic的talk分享，交流想法
- 论文：团队研究成果
- Demo：团队技术成果展示

## 博客更新
1. 博客以md形式存储，图片、视频通过外链的方式嵌入。具体可以参考/_post/2025-04-22-Structurization.md文件中的方式
2. md开头需要增加如下的头结构，layout必须是post，title为博客标题，short_description为简介，会展示在博客板块列表中。后续按照正常md结构编写即可
```
---
layout: post
title: 博客名称
short_description: 这篇博客介绍了xxx，探讨对于压缩即智能的理解
---

Markdown Content
```
4. 注意的是：
   - 文件名称按照YYYY-MM-DD-Name.md命名，这样日期会自动显示在博客板块的结构中
   - 避免将图片、视频、数据等大文件嵌入md并上传，通过云盘提供外链支持大文件展示

## 论文更新
1. 更新papers.md即可
2. 注意不要修改头结构

## Demo更新
TODO: Demo板块的分页处理

## 更多定制化开发
- 文件结构介绍
- Github Pages的相关经验

# 更新日志
