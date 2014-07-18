---
layout: post
published: true
title: Jekyll + Prose.io
mathjax: false
featured: true
comments: false
headline: Making blogging easier for masses
categories: 
  - webdevelopment
tags: jekyll
---

Nothing beats Medium when it comes to blogging. Its overly simplistic, minimal and its true WYSIWYG editor put itself ahead of the races. But there comes a time, when you might need a self hosted blog. Maybe its for a project, or as it was for me, I needed something static to be hosted in my University’s servers.

It was 2008, I was a freshman at college and I was provided with a University email id and a small web-hosting space. I did not pay as much heed to the latter one until I was required to put up some notes on it by my EECS-I course instructor. I was involved in a robotics project, and my CI wanted me to post regular updates on my provided web-space. During the first four weeks of classes, we were given a short course on Git Version Control, but for blogging, I did not know where to start. I Googled, and I found WordPress, it seemed perfect for the job at hand, I downloaded the latest version from the repository and unzipped the contents on my web-space, when I went on to install it, I found that student web-spaces did not support dynamic pages and builds. What a bummer.

So I made a simple HTML document in notepad, and painstakingly put the contents I was supposed to put on, without any CSS styling. It was ugly, but it got the job done. Updating the page with newer contents was pain, as I would have to edit it manually and upload and replace the older file. I kept looking for a better solution, but I did not ask anyone for help, then suddenly I came upon a Python based static site generator. It was my first semester, I was learning Python, so obviously I got enthusiastic about using the tool. I made a blog in my university domain with it and t helped me gain a little bit of street credit. But I was never really happy with the workflow with it.

Then I found Jekyll, a true gem written in Ruby. I never took Ruby lessons, yet the code base which contained 16K LoC was easier to understand, and the usage was much more easier. I had to install Ruby, the corresponding Ruby DevKit and Jekyll locally on my machine to get my site up and running. Also, I could only publish from my machine only as that was the only machine had all the tools installed to compile a Jekyll site.

This mode of workflow meant I was never truly mobile when it came to blogging. I always have