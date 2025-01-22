---
layout: post
title: My own Jekyll theme
date: 2025-01-22 18:06 +0100
tags: code github site
---

Every GitHub Pages blog starts out with the default Minima theme, which looks ugly, boring, and, well... default.

So I started looking to other themes. The default Pages gem mostly contains documentation themes without a post index. I liked the look of the `hacker` theme, as I am an avid Retro enjoyer. I soon found a Retro Windows 95 theme, but it was old and broken, and my attempts at repairing it led to not much. So, I started writing my own Jekyll theme.

The basic idea was clear pretty soon: I wanted it to look and be clean and simple, both in and out, and it should support blogging. I got inspiration from the layout of [XKCD], with its cleanly divided blocks. So, I fired up WebStorm, and started writing, with great help from Copilot. The 404 and Home pages I "borrowed" from Minima, with some changes to suit me. The site started with HTML and CSS, but I soon switched to SCSS for its modularity.

The first iteration, however, was heavily criticised for its ugly color theme. So, I got human help, and together, [Micodo] and I created a clean, dark but colored, color scheme.

Then came chaos: I decided to split the theme from the blog, and publish it to RubyGems. My first attempt at using `git subtree` ended miserably, as moving files does not retain history. In an effort that took an entire afternoon, I rebased my edits onto a copy of the original repository, and meticoulously edited history to make it seem like I had planned this all the time. And finally, it worked: The history now accurately shows the development of my own Jekyll theme.

You can use it too! Simply follow the [instructions] in its GitHub Repository (or on the Page built from it), and make sure your Page uses a [Gem build].
	
[XKCD]: https://xkcd.com
[instructions]: https://libewa.xyz/jekyll-glass
[Gem build]: https://jekyllrb.com/docs/continuous-integration/github-actions/