--- 
title: The Simple Joy of a Static Site
layout: post
published: false
---
The more I've wanted to write over the past few months, the more I've wanted to find a better place to do it. Over the past seven years, I've used TypePad, WordPress, Tumblr and some of the lesser-known, now-defunct tools. Each has served me well in different ways, but eventually you realize that all of these services change over time, often evolving into something that doesn't work for you anymore. Others simply fade away. 

Whereas we once spent a lot of time trying to figure out how to make sure our online content would always be available (see [permalinks](http://en.wikipedia.org/wiki/Permalink)), it seems most of us have come to terms with the ephemeral nature of today's web. Twitter doesn't know why you would want access to all of your tweets, photos are shared on services that don't even require an account, few site redesigns take into account the broken links that may result, and millions of links are shared through URL shorteners that will likely not exist in five years.

I don't think this is a healthy trend for the web. We're slowly being trained to devalue the content we create, which only makes us more casual about creating it. This certainly leads us to share more content, and there's good in that (certainly for the companies who profit from it), but it's hard to argue it's better content.

I want to think about this more, but in my case, it's led me to want to own my content. Inspired by [this post by Marco Arment](http://www.marco.org/2011/07/11/own-your-identity), I want my words to be on my hard drive and readable on my domain. I want to be able to easily switch to another host without having to worry about what would be involved in the switch and the possibility of losing my content. I want to able to write posts using [iA Writer](http://www.iawriter.com/) and Markdown.

I set out to find the perfect solution and started a few different experiments. What I hoped to find was something that I could understand and customize completely. There's a lot of power that comes with that. I quickly discovered that hosting your own version of Wordpress or using one of the many fine Ruby on Rails blogging tools involves far too much complication and troublesome dependencies that get in the way of actually writing. Issues of database configuration, gem and Ruby versions, security, and deployment. The bigger concern, though, was maintaining the site through upgrades, patches and changes to my local environment as well as the server. I don't need any fresh excuses for not writing.

Thankfully, I came across a few posts extolling the virtues of static sites, including these by [Amazon's Werner Vogels](http://www.allthingsdistributed.com/2011/02/website_amazon_s3.html). A static site (each post and page is simple HTML and isn't generated dynamically from a database) is a throwback to the early days of the web. It's basically like listening to vinyl records in the age of MP3s. 

The benefits are speed (there's so little involved in rendering a single page of HTML that things load quickly) and simplicity. You can host the site pretty much anywhere you want and little can go wrong. The essentials are easy and the non-essentials are just difficult enough to discourage you from messing up the simplicity.

After a great deal of research, I settled on [Jekyll hosted on GitHub](https://github.com/mojombo/jekyll). You can take a [look at the new site here](http://brianbailey.me). More on the decision and transition shortly.