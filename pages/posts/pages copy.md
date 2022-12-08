---
title: Next.js Pages
date: 2021/3/18
description: Learn more about Next.js pages.
tag: web development
author: You
---

#### Scenario 2: Your page paths depend on external data

Next.js allows you to create pages with **dynamic routes**. For example, you can create a file called `pages/posts/[id].js` to show a single blog post based on `id`. This will allow you to show a blog post with `id: 1` when you access `posts/1`.

> To learn more about dynamic routing, check the [Dynamic Routing documentation](/docs/routing/dynamic-routes.md).

However, which `id` you want to pre-render at build time might depend on external data.

