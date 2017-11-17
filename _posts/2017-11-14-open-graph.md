---
layout: post
title:  "Implementing comments & Open Graph "
date:   2017-11-14 08:00:08 +0100
categories: jekyll update
author: Kajsa Lindelöw
---

### How did you implement comments to blog posts?

To include some user interaction to my static site I decided to use Disqus, which is a free service that lets you implement a commentary feed into your blog. I followed the guide available on Disqus’ homepage, created an account and copied the code snippets that they provide for you. I put those into my layout for post. In the YAML front matter of the same page I added ”comments: true”, in order to include a commentary feed into each blogpost.


### What is Open Graph and how do you make use of it?

Open Graph is a protocol which you can use to control how your website will look in a social graph (for example Facebook). You create this graph object by using specific meta data in the head of your website. There are four required properties:

{% highlight ruby %}
og: title - The title of your object.
og: type - The type of your object (for example - a website, blog post or video)
og: image- An image url which represents your object.
og: url- The url of your object. 
{% endhighlight %}

For my website I found it enough to use only these four required properties. If you have a larger website with more content you might want to add more properties to choose from. There are intact a lot of optional data you can add, like audio, site name, description etc.
