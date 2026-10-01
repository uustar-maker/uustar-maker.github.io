# 心屿 —— 部署指南

## 第一步：在 GitHub 新建仓库

1. 登录 GitHub，点右上角 `+` → New repository
2. 仓库名必须填：`你的用户名.github.io`（例如 `zhangsan.github.io`）
3. 选 Public，点 Create repository

## 第二步：上传这些文件

把本文件夹里的所有文件上传到仓库根目录（网页操作：Add file → Upload files，把文件拖进去就行）。

## 第三步：开启 Pages

仓库 → Settings → Pages → Source 选 "Deploy from a branch"，分支选 main，点 Save。

## 第四步：访问

等一两分钟，打开 `https://你的用户名.github.io` 就能看到博客了。

## 以后写新文章

在 `_posts` 文件夹新建文件，命名格式：`年-月-日-英文标题.md`，例如 `2026-10-05-xinqing.md`，文件开头写：

```
---
layout: post
title: "文章标题"
date: 2026-10-05 20:00:00 +0800
categories: 随笔
---
```

然后正文用 Markdown 写，保存上传就行。

## 改博客名字 / 笔名

改 `_config.yml` 里的 `title`、`description`、`author`，以及把 `USERNAME` 换成你的 GitHub 用户名。
