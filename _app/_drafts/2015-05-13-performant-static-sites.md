---
layout: post
title: Performant Websites
category: blog
hidden: true
---

## Static: The right choice for the future

There are many compelling reasons why you should go static for your personal website. I'll get straight to the point and say the most important reason is <code>Performance</code>. Moving away from WordPress or any CMS meant that content need not be dynamically rendered and that there was no longer a database in question. What this means is that once a visitor hits your URL, instead of the server having to access the information from storage / memory and running queries to render your page, the static content gets immediately served. This leads to performance of a whole new level.

The implication of going static would be the ease of workflow - <em>especially</em> if you have multiple authors, or are unwilling to get your hands dirty with things like git, etc.

It's also important to note that page load times are factored in search engine ranking, and for that matter, whether your site is SSL secured too. Having technology advances like SSL, although it means additional security, it also meant that round trips between client and server is necessary for that authentication. Since this is inevitable, going static can decrease your page load times as much as possible <strong>after</strong> SSL negotiation occurs.

## Static Site Generator - Jekyll & AMSF
Aside from having enjoyed Jekyll and Hyde recently, there are compelling reasons why Jekyll was perfect for the job as a static site generator.

- Runs on Ruby 
- Great plugins and workflows available
- Lots of development activity, always updated
- Write in Markdown

The framework I've quite shamelessly used without much changes is AMSF. It's just 1 html page with 1 request, and having a small page size meant <strong>insane</strong> page load times. If you don't believe me, here is a screencap.

<img src="{{ site.img }}/gtmetrix.png" alt="GTMetrix Score">

## Choosing a good host

<code>To be continued..</code>