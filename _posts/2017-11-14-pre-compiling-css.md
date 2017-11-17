---
layout: post
title:  "Pre-compiling CSS & static site generators"
date:   2017-11-14 08:05:08 +0100
categories: jekyll update
author: Kajsa Lindelöw
---
### Pre-compiling my CSS

##### What do you think of pre-compiling your CSS, compared to regular CSS? 
Using a CSS preprocessor makes it a lot easier writing code in a clear and structured way. It reduces the amount of code and I don’t have to repeat myself (DRY) as much as in regular CSS, due to  the greater amount of functionality offered by the CSS preprocessors. It also makes it easier to find certain elements which, together with the reduced amount of code, makes the code easier to maintain. I really enjoyed this way of structuring my code, and compared to regular CSS I found it a lot more easy to work with.


##### Which techniques have you used?
For this project I used the CSS preprocessor Sass together with the syntax SCSS, and I really enjoyed trying out the basics features. I’ve worked mainly with variables and nesting,but also learned a lot by modifying and adding new styles to the existing minima SCSS-file, which I copied and used as a foundation for this website.

##### Pros and cons?
I’ve already mentioned some of the advantages with pre-compiling my CSS. I really like the fact that my code gets more readable and that I don’t have to repeat myself. I also like the fact that I don’t have to make changes in multiple files, often it’s enough changing in one place if I’ve already defined a variable.There are also some disadvantages though. It gets a bit harder debugging the code (although there are programs solving this problem) and you need to add more tools to be able to compile your code. It also adds a new syntax to learn, which can create problem if you work in a team where you use different syntaxes (for example Sass or Less). Regular CSS is more likely to be understood and used by most people.

### Static site generators

##### What do you think of static site generators? What type of projects are they suitable for?
I think a static site generator (like Jekyll that I used for this project) is great when you want to create a website without demands for user integration. It’s quite easy to build and maintain a website and its more secure than a dynamic site because of the non existing user integration, which means that you don’t need to worry about being hacked. A static site generator is suitable for example creating a blog, or any other site where you don’t need dynamic content like logins, member registration etc.
