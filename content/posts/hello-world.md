---
title: "第一篇"
date: 2026-10-23T09:00:00+08:00
draft: false
tags: ["随笔"]
categories: ["日常"]
summary: "站点跑起来了。先占个位，顺手记一下怎么发下一篇。"
---

站点跑起来了。

## 怎么发新文章

在 GitHub 仓库里进 `content/posts/`，点 **Add file → Create new file**，文件名用英文或拼音加 `.md`（比如 `my-first-post.md`），内容照着下面这个格式写：

```markdown
---
title: "文章标题"
date: 2026-10-23T20:00:00+08:00
draft: false
tags: ["标签一", "标签二"]
categories: ["分类"]
summary: "一句话摘要，会显示在列表页。"
---

正文从这里开始。
```

写完点 **Commit changes**，等一两分钟，Cloudflare 会自动构建部署，刷新页面就能看到。

## 几个约定

- `draft: true` 的文章不会发布，想先存着就设成 `true`
- 文件名建议全小写、用连字符，别用中文和空格
- `tags` 和 `categories` 决定文章会出现在哪个分类页
- 正文用 Markdown 写，标题、列表、代码块、图片都支持

就先这样。
