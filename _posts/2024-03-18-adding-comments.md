---
title: "Adding Comments"
categories:
  - Blog
tags:
  - GitHub Pages
  - Minimal Mistakes
  - Meta
---

This blog now includes a comment system! There are a few projects out there that work to add commenting to static pages hosted on GitHub pages. Below are a few such projects and my thoughts on them:

- [Disqus](https://disqus.com/)
  - This is a very popular commenting framework and can work well but is proprietary and requires an account.
  - The basic tier is also ad supported which I am not a fan of for privacy reasons.
- [Discourse](https://www.discourse.org/)
  - Another common commenting system, also requires an account and creates a forum style page for you to host conversations on.
  - This is a bit heavy for what I want but can be a good option and is self-hostable.
- Facebook comments
  - Easy to get set up but I don't have a Facebook account and don't particularly want to force my users to make one just to comment.
- [Utterances](https://utteranc.es/)
  - Uses github issues to host comments. Requires a GitHub account to comment.
- [giscus](https://giscus.app/)
  - Very similar to Utterances but uses GitHub Discussions instead of issues. Also requires a GitHub account to comment.
- [Staticman]
  - This project requires self-hosting and uses GitHub issues behind the scenes for storing content.
  - This is a project I have a soft spot for as I used to be a maintainer of the project, but it hasn't seen active development for some time now.

Given all of the options I've explored have some trade-offs, I eventually landed on giscus. It's pretty simple to set up and uses GitHub Discussions, which seems like a reasonable place for comment threads to go. It does require commenters to have a GitHub account, which is something I wanted to avoid, but this should help combat spam to some degree and at this time is an acceptable trade-off for me. There's also an option to self-host which I will likely explore in the future.

If you use Minimal Mistakes theme, the setup for all of these commenting systems is quite easy. To get started with giscus on Minimal Mistakes, see their [docs on the subject](https://mmistakes.github.io/minimal-mistakes/docs/configuration/#giscus-comments). If you use another theme don't worry, it's still pretty simple to get started by following the official [giscus docs](https://giscus.app/).

If there are other approaches for commenting on static sites you like that I didn't cover, let me know in the comments!
