---
layout: post
title: "Day 01 - Shall we be friends?"
date: 2017-02-24
categories:
  - Personal
description:
image: http://jacobsalzberg.github.io/db/static/path_2000.jpg
image-sm: http://jacobsalzberg.github.io/db/static/path_500.jpg
---


# "Hello, world."
---
###  >>SAO PAULO, FEB. 24th 2017<<
---
<br><br>

### Why are we here?
I'll keep this updated for the sake of my mental health. Also, it's a decent tool to keep track of my skills development and general life hacks or just random rant. Most developers have a blog so.. why the hell can't I have one too? I feel like I'm talking to myself, but venting out definitely helps.


#### My first blog: About my day
I took most of the day off to find out how to get this *stupid* blog rolling (hello there, let's try to be friends, Mr. CL4PTR4P). In order to do so, as I found a great Jekyll theme, I had to setup linux on my laptop as it's required for Jekyll.

![CL4PT4P](https://m.popkey.co/530e0a/XRjLe.gif "Hey there")




* Basic **rewind on Linux** - I decided to install mint 18.1 with cinnamon. I had some experience but I had to get used to the terminal again;
* **Git** usage on bash (mint's gnome based terminal)
* **Jekyll + Bundler** general usage;
* Adding **Gem-Based themes**;
* **Markdown** (.md) synax - it's ultra easy, it's the synax im using to write this post with. It pretty much converts given symbols into html, making it ultra readable;

It was a pretty rough ride as I had a lot of issues with gems, mostly related to bad documentation on the theme's end and I had zero previous experience with this. I ended up fixing my problems by using `sudo bundle update` after cloning the theme's source repo. It literally took me about 4 hours of tweaking and face-smashing the terminal to get this ready, as the general fix-suggestions made no sense.

But oh well, at last, the blog is running _silky smooth_. After getting the theme all sorted and github pages ready, here's the flow I'll be using to post on it:

1. Fully edit the post on W10 using Haroopad or atom (it's faster, better keyboard than my laptop);
2. Manually upload the post to github it's faster than using git bash also the images in the static folder;
3. On linux (given you're already on the correct brach, which should be **gh-pages**):
  * **sudo git status** - check if the files were upload properly
  * **sudo git pull**   - clones the changes the local folder
  * **sudo bundle exec jekyll build**  - builds the blog ![Alt](http://jacobsalzberg.github.io/db/static/bexec.png "Hello, terminal!")
  * **sudo git add .** - adds all .html files and other files that were generated
  * **sudo git commit -m "random commit message"** - commits the changes
  * **sudo git push -u origin gh-pages** - pushes them to github

And that's it. Blog is running really fine.<br>

### Lessons Learned
I really need to work on my multi-tasking skills. I "tunnel" (short of "tunnel vision": *[informal] the tendency to focus exclusively on a single or limited goal or point of view*) too much if there's an issue - if I can't get it solved, I keep trying over and over and over, even if I should be doing something else. This is (somewhat) fine, but not if I'm not moving on the direction of fixing the given issue.

### Blog plans and Ending
As for now, I'll start with two blog categories:
* Personal, for my personal updates (yes, as if it was impossible to guess what it was about with such a creative name) and;
* DevBlog, for game-specific updates;

<br>
Let's see how it goes. Just to make this pretty, I'll add a quote:

<blockquote>"Life is short and we have never too much time for gladdening the hearts of those who are travelling the dark journey with us. Oh be swift to love, make haste to be kind."  
<cite>Henri Frederic Amiel</cite></blockquote>

This will be a really tough ride. As hard as it will be, I'll do my best and be kind to those around me. Thanks for your time.

***
PS: Art is by k04sk: [DA](http://k04sk.deviantart.com/art/Path-333698884)
