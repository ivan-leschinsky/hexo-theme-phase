# Phase
Feel the flow of time with Phase, the most beautiful theme for [Hexo].

## Install
Execute the following command and modify `theme` in `_config.yml` to `phase`.
```
git clone https://github.com/lbkmono/hexo-theme-phase themes/phase
```

## Update
Execute the following command to update Light.
```
cd themes/phase
git pull
```

## Features
- [Phase Beam](https://www.youtube.com/watch?v=NhCXnWeXDT0) live background.
- Read `alt` property of photos and add it below photos.
- Built-in [Fancybox](http://fancyapps.com/fancybox/) enables you to show your works easily.
- Resize HTML5 `video` and embedded video like `iframe`, `object` to page width automatically.
[Hexo]: http://zespia.tw/hexo

## Language
- Make sure to configure language to be "default" for English inside _config.yml of the blog directory e.g. .../blog/; **not** the _config.yml inside .../blog/themes/phase
```
# Site
title: Hexo
subtitle:
description:
author: John Doe
language: default
timezone:
```

## Syntax
- Adding comments (disqus) to posts/pages:
Add inside _config.yml of the BLOG directory
```
disqus_shortname: disqus_shortname_here
```

- Adding Tags/Categories to Posts
Inside the markdown (md) files of each post:
```
title: post title
date: mm/dd/yyyy
categories:
- category 1
- category 2
tags:
- tag 1
- tag 2
---
```

- Using fancy box Images
Inside the markdown (md) file of each post, add:
```
photos:
- photo_1_url.jpg
- photo_2_url.jpg
```

## Bug Fixes 
* Fixed issue with fancybox for pages (non-posts)


