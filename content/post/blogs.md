---
title: "Blogs"
subtitle: "Thoughts on blogs"
date: 2023-08-17T16:22:46+03:00 # post date
toc: true # table of contents (only h2 and h3 added to toc)
bold: false # display post title in bold in posts list
math: false # load katex
# categories
categories:
  - thoughts
# tags
tags:
  - blog
next: false # show link to next post in footer
nomenu: false # hide site menu
notitle: false # hide title
---

## About this blog

This blog was created with [Hugo](https://gohugo.io/) and [Dead simple theme](https://github.com/barklan/hugo-dead-simple). I tried multiple ways to create blog, but all of them were too complicated for it. My options were [Rocket](https://rocket.rs/), written from scratch C static site generator, written from scratch Rust static site generator. Rocket website was too slow for me and the framework obviously was not made for blogs. Just try thinking about adding keywords to a dynamic website. It was really bad experience. C SSG as you may expect was too low-level. Rust SSG was the best one, but the issue was that there was no community and custom themes/plugins, that Hugo has. Therefore I think that Hugo is the best option for building blogs for its ease of use and community support.

## My blog reading setup

I read blogs too, so I think it may be helpful fore someone who finds this post to share my blog reading setup. As most people I use [RSS](https://en.wikipedia.org/wiki/RSS) to track new posts. [Newsboat](https://wiki.archlinux.org/title/Newsboat) for PC and [Feeder](https://f-droid.org/packages/com.nononsenseapps.feeder/) for my Android phone. There is a lot of different apps that can provide RSS feed reader, so I suggest you to make your own research on this topic.

{{< box info >}}
**Add this blog to your rss feeds**

[Here](/index.xml) is my RSS feed
{{< /box >}}

My current newsboat urls ( `~/.config/newsboat/urls` ):

```
https://lukesmith.xyz/rss.xml
https://based.cooking/index.xml
https://www.archlinux.org/feeds/news/
https://j3s.sh/feed.atom
https://pudding.cool/rss.xml
https://drewdevault.com/blog/index.xml
https://ciechanow.ski/atom.xml
https://sizeof.cat/index.xml
https://www.igalia.com/chats.xml
https://100r.co/links/rss.xml
```

## Make your own website

You can make yourself a website like this by following [this](https://rxsamira.netlify.app/post/hugo-dead-simple/) installation guide.
