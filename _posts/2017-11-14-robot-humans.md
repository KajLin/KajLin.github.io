---
layout: post
title:  "Robot.txt & Humans.txt"
date:   2017-11-14 07:05:08 +0100
categories: jekyll update
author: Kajsa Lindelöw
---
##### What is robots.txt and how have you configure it for your site?

Robots.txt is a file that you find in the root of the website. With this configuration you can decide if you want to allow web robots to visit your pages/site. When the robot wants to visit your site, it first checks for the robots.txt. For my website I’ve configured my robots.txt to disallow all robots. 


{% highlight ruby %}
User-agent: *
Disallow: /
{% endhighlight %}


##### What is humans.txt and how have you configured it?
Humans.txt is a file where you add information about your website. You can specify information about the team, owner, contact, development tools etc. I have configured my humans.txt by adding short information about me and how to contact me and information about the development tools I’ve used in this project.
