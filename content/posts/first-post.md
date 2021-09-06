---
title: "Site Redesign"
date: 2021-09-05T23:52:34-07:00
draft: false
author: "chris"
---

![New Hugo Site!](/posts/new_hugo_site.png)

Hello all;

I decided that I was going to start from scratch and rebuild the whole site. I am still going with a static site generation because its quick, easy and convenient to deploy.

I switched from [Pelican](https://github.com/getpelican/pelican) over to [Hugo](https://gohugo.io/) for a couple of reasons:

1. Pelican simply doesn't have the community and following that Hugo and Gatsby seem to, anyone who has spent time with open source software knows, bigger community = better support = better documentation...etc.
2. I always had issues getting themeing with Pelican to work on Netlify, which is my perfered deployment option for static sites, although [Surge](https://surge.sh/) seems really cool and I want to mess with that at some point.
3. Hugo had a simple and clean [theme](https://hugoloveit.com/) that I fell in love with right off the bat and it was pretty well documented and easy to configure. 
4. Pelican's main selling point for me is that it was written in python, but I never had to go under the hood and start writing any python. I mean the whole point of a static site generator is that you *don't* have to write any code, just drop some markdown in and go.

I won't be long winded on how I set all this up, hugo's [documentation](https://gohugo.io/getting-started/quick-start/) is extremely friendly and the theme's is as well. On Ubuntu both APT and Snap(if that is your thing) have packages ready to roll.

I do have one pro-tip though, if you are a WSL user, hugo is kind of a pain to get running (not sure if this was just on my system or a global issue), I had zero issues once I booted into an Ubuntu 20.04 VM.