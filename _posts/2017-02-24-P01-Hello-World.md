---
layout: post
title: "Day 01 - Shall we be friends?"
date: 2017-02-19
categories:
  - Personal
description:
image: https://unsplash.it/2000/1200?image=1003
image-sm: https://unsplash.it/500/300?image=1003
---


# "Hello, world."

 ### >>SAO PAULO, 2017 FEB. 24
 ---

I'll keep this updated for the sake of my mental health, to keep track of my skills development and general life hacks or just random rant. So here it goes.. I took most of the day off to find out how to get this *stupid* blog rolling (hello there, let's try to be friends, Mr. CL4PTR4P). In order to do so, as I found a great Jekyll theme, I had to setup linux on my laptop as it's required for Jekyll.

So I pretty much ended up learning:

* Basic **rewind on Linux** - I decided to install mint 18.1 with cinnamon. I had some experience but I had to get used to the terminal again;
* **Gi**t usage on bash (mint's gnome based terminal)
* **Jekyll + Bundler** general usage;
* Adding **Gem-Based themes**;
* **Markdown** (.md) synax - it's ultra easy, it's the synax im using to write this post with. It pretty much converts given symbols into html, making it ultra readable;

It was a pretty rough ride as I had a lot of issues with gems, mostly related to bad documentation on the theme's end and I had zero previous experience with this. I ended up fixing my problems by using `sudo bundle update` after cloning the theme's source repo. It literally took me about 4 hours of tweaking and face-smashing the terminal to get this ready, as the general fix-suggestions made no sense.

I really need to work on my multi-tasking skills. I "tunnel" (short of "tunnel vision": *[informal] the tendency to focus exclusively on a single or limited goal or point of view*) too much if there's an issue - if I can't get it solved, I keep trying over and over and over, even if I should be doing something else. This is (somewhat) fine, but not if I'm not moving on the direction of fixing the given issue.

But oh well, at last, the blog is running _silky smooth_. After getting the theme all sorted and github pages ready, here's the flow I'll be using to post on it:

1. Fully edit the post on W10 using Haroopad (it's faster, better keyboard than my laptop);
2. Manually upload the post to github it's faster than using git bash also the images in the static folder;
3. On linux (given you're already on the correct brach, which should be **gh-pages**):
  * `sudo git status` - check if the files were upload properly
  * `sudo git pull`   - clones the changes the local folder
  * `sudo bundle exec jekyll build`  - builds the blog ![Alt](/static/bexec.png "Hello, terminal!")
  * `sudo git add .` - adds all .html files and other files that were generated
  * `sudo git commit -m "random commit message"` - commits the changes
  * `sudo git push -u origin gh-pages` - pushes them to github

And that's it.











