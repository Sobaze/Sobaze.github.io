---
layout: post
title:  "Robots.txt"
author: Jonas
date:   2019-11-12 07:25:14 -0600
categories: jekyll update
---
What is robots.txt and how did I configure it on my site?

Is a way for us to give instructions about your site to the web robots. 
For example if a robots wants to visit a web site url, it first goes and inspect the robots.txt page.
There it can see something that could look like this: 
User-agent: *
Disallow: /
The user-agent: * applies to all robots and the "disallow: / " part tells the robot that it should ot visit any pages of the site.
Spammers often use robots to scan for peoples email adresses.
It is also easy to see where you don't want to allow robots since the files are public. This can be risky so it's better to hide information in another way than robots.txt. There is also programs such as "screaming frog" that can ignore the robots files it founds.

I chose to have my robots.txt file to exclude all robots from my enitre server, my reasoning behind this is if my site attracts to many of these crawlers it has a chance to lower the speed of my site. So to make my readers not experiencing the page slowing down and instead enjoy my content only.