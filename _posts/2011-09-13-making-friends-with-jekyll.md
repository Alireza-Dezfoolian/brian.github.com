--- 
title: Making Friends With Jekyll
layout: post
---

This site is built using the [Jekyll content generator](https://github.com/mojombo/jekyll/wiki) and hosted on [GitHub](https://github.com). I [wrote recently](http://brianbailey.me/2011/09/03/the-simple-joy-of-a-static-site/) about moving my writing to a simple, static site that doesn't use a database, can be deployed anywhere, and allows me complete control over the content. Here's how I landed on Jekyll.

My search was limited to tools that use Ruby since it's the language I'm most familiar with and the community and resources around it are so helpful. The first three options I considered were [Nesta](http://nestacms.com/), [nanoc](http://nanoc.stoneship.org/), and [toto](http://cloudhead.io/toto). Each has its benefits. Of the three, toto is the most simple and limited (in a good way). Nesta and toto each make it easy to deploy to [Heroku](http://heroku.com), so a version-controlled, free site is possible in about five minutes. I'd recommend trying all of these, and any of many other options you come across, because you never know why one tool will click with you while another one won't.

I actually found Jekyll because I loved the design of [Tom Preston-Werner's site](http://tom.preston-werner.com/), the creator of Jekyll. For the past few months I've been bookmarking blogs and sites with designs that really appeal to me. Every month, my preferences just kept getting simpler. I just want readable text on a page; no columns, no mixed content, just words. In the end, they are all that matter.

The magic moment was when I realized that Tom's [entire site is on GitHub](https://github.com/mojombo/mojombo.github.com). Instead of jumping into a tool without any context, I could download the source code and immediately have a working site with great examples of how to accomplish all the elements that make up a site (archives, syndication, navigation). It was a massive help and as you can see, I largely emulated his style and structure.

People who use Jekyll love to write blog posts about using Jekyll, which made it very easy to get up and running.  Here are some of the posts I've found most helpful:

+ [Jekyll configuration](https://github.com/mojombo/jekyll/wiki/configuration)
+ [Available plugins](https://github.com/mojombo/jekyll/wiki/Plugins)
+ [My favorite walkthrough](http://klepas.org/jekyll-a-static-site-generator/)
+ [Handy tips and a dead-simple archive option](http://orgmode.org/worg/org-tutorials/org-jekyll.html)
+ [Migrating from Wordpress to Jekyll](http://vitobotta.com/how-to-migrate-from-wordpress-to-jekyll/)
+ [GitHub Pages](http://pages.github.com/) and a related [walkthrough](http://www.alexrothenberg.com/2011/01/27/moved-blog-to-jekyll-and-github-pages.html)
+ The most wonderful discovery of all: a [script to import posts from TypePad](https://github.com/dams/typepad_to_jekyll)

The beauty of Jekyll and Ruby is everything makes a great deal of sense. When you imagine the most straightforward solution to something, you're usually right. Having access to the source code of [so many different Jekyll sites](https://github.com/mojombo/jekyll/wiki/Sites) is a big help if you get stumped. I've found that usually getting stumped means it's not worth it, though. I spent a few hours working with various category and tagging options until I decided that I have no reason for them. And if I ever find myself typing 'Jekyll sidebar widgets' in my search bar, well, it's time to hang it up.

The best part of this experience has been working on it with my son, Ben. He has been experimenting with different site tools as well and fell in love with Jekyll along with me. Over the next week, we spent quite a few hours learning the ins and outs together, customizing our sites, trying new things, and sharing how-tos. He even took his site one step further and is hosting it on Amazon's S3. You can [see it here](http://blog.benbailey.me/archive/).

You'll find the full source of [brianbailey.me on GitHub](https://github.com/brian/brian.github.com). Grab your own copy and then make it your own.
