---
title: "你好，ShowWhen"
published: 2026-09-25
description: "博客正式开张。这篇文章介绍 ShowWhen 的由来，以及这个博客支持的写作玩法。"
tags: ["随笔", "博客"]
category: "生活"
draft: false
---

欢迎来到 **ShowWhen** —— 一个用 [Astro](https://astro.build/) 与 [Fuwari](https://github.com/saicaca/fuwari) 模板搭建的静态博客。

域名叫 showwhen.top，意思是「展示何时」：什么时候学了新东西、什么时候去了新地方、什么时候冒出了新想法，都记在这里。

## 为什么写博客

:::tip
写下来，才算真正想清楚。
:::

社交媒体的内容像水流，博客的内容像石头。我希望这里存放的是经过沉淀的东西：

- 技术学习的笔记与踩坑记录
- 读书、观影与旅行的感受
- 对生活的一些观察和思考

## 这个博客支持什么

这个主题看起来简洁，功能却一点都不少。

### 代码高亮

```typescript
// 新建文章：pnpm new-post 我的文章标题
function greet(name: string): string {
  return `你好，${name}！`;
}

console.log(greet("ShowWhen"));
```

### 提示框

:::note
这是一条普通备注（note）。
:::

:::important
重要信息会用这样的块突出显示。
:::

:::warning
警告信息适合放需要格外留意的内容。
:::

### 数学公式

行内公式如 $E = mc^2$，独立公式：

$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$

### 引用与列表

> 种一棵树最好的时间是十年前，其次是现在。

1. 想好要写的主题
2. 用 Markdown 写成文章
3. 推送到 GitHub，网站自动更新

## 如何开始写新文章

在项目目录下运行：

```shell
pnpm new-post 我的第一篇文章
```

然后在 `src/content/posts/` 下编辑生成的 Markdown 文件，写完 `git push`，GitHub Actions 会自动构建并发布。

---

那么，就从这里开始吧。
