---
layout: post
title: "Post: Future Date"
date: 9999-12-31
categories:
  - Post
last_modified_at: ''
---

This post lives in the future and is dated {{ page.date | date: "%c" }}. It should only appear when Jekyll builds your project with the `--future` flag.

```bash
jekyll build --future
```