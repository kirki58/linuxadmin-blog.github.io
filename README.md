# linuxadmin.blog 🐧 [![Deploy Hugo site to Pages](https://github.com/linuxadmin-blog/linuxadmin-blog.github.io/actions/workflows/hugo.yaml/badge.svg?branch=master)](https://github.com/linuxadmin-blog/linuxadmin-blog.github.io/actions/workflows/hugo.yaml)

[linuxadmin.blog](https://linuxadmin.blog) is a collective space where webmasters can share knowledge about security, virtualization and automation.

The site is created with [Hugo](https://gohugo.io) using [terminal.css](https://github.com/panr/hugo-theme-terminal). And hosted by [GitHub Pages](https://pages.github.com/).

## Contributing

To create a blog post of your own is easy as creating a file:

```sh
$ git clone https://github.com/linuxadmin-blog/linuxadmin-blog.github.io.git ~/linuxadmin-blog
$ cd ~/linuxadmin-blog && touch ~/linuxadmin-blog/content/posts/<your-post-title>.md
```

And publishing it much more easier:

```sh
$ git add ~/linuxadmin-blog/content/posts/<your-post-title>.md
$ git commit -m "added new post: <your-post-title>"
$ git push
```

Post format:

```md
---
title: "<your-post-title>"
date: YYYY-MM-DD
author: "<your-name>"
tags: ["<example>", "<tags>"]
categories: ["<category-name>"]
draft: false
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed eu porta sapien.
Vivamus sapien lectus, efficitur a felis in, porta gravida magna.
Suspendisse suscipit id quam maximus euismod.
Nam odio erat, efficitur eu sodales vel, ultrices eu orci.
Curabitur tincidunt ac libero nec varius...
```
