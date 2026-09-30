# 雫之绒野 · rongye.icu

安静的个人博客。冷调纸白 + 银蓝 + 灰蓝，杂志式书房风格。

## 快速开始

```bash
npm install
npm run dev      # 开发预览 http://localhost:4321
npm run build    # 输出静态站点到 dist/
npm run preview  # 预览构建结果
```

## 替换头像

把头像文件放到 `public/images/avatar.jpg`。
支持 jpg / png / webp，建议 400×400 以上方形图片。

## 写新文章

在 `src/content/posts/` 新建 Markdown 文件，文件名建议 `YYYY-MM-DD-slug.md`：

```markdown
---
title: 文章标题
date: 2025-03-08
summary: 一两句摘要，会显示在列表页。
tags: [随笔, 日常]
draft: false
---

正文从这里开始。
```

## 修改友链 / 图库

- 友链：`src/data/friends.ts`
- 图库：`src/data/gallery.ts`

## 站点信息

站点标题、副标题、邮箱等配置在 `src/data/site.ts`。
