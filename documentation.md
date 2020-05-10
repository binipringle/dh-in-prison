---
layout: page
title: Documentation
author: Sabina Pringle
source: Ed documentation by Alex Gil
---

## Contents
{:.no_toc}

* ToC
{:toc}

---

This is a static site built with Jekyll using the [Ed](https://elotroalex.github.io/ed/documentation/) Jekyll theme.

To make a copy of this site and run it on your computer without an internet connection, you will need to use your terminal. If you need a refresher, I recommend "[Introduction to the Command Line](https://github.com/GC-DRI/command-line)." Once you are in your terminal, try this (this is the "easy" or "lucky" way to install):

Create a folder in your Desktop where you want your copy of this site to be. I would call my folder 'projects.' When you have created your folder (or directory), go into it with the cd (change directory) command, like this:


~~~ bash
$ cd Desktop
$ mkdir projects
$ cd projects
~~~

Now type or paste the following commands:

~~~ bash
$ git clone https://github.com/binipringle/dh-in-prison.git
$ cd dh-in-prison
$ gem install bundler
$ bundle install
~~~

Done. To see if DH in Prison is working properly, tell Jekyll to serve by typing

~~~ bash
$ jekyll serve
~~~

If at any point during this process you had an error you could not resolve, see below. If the site was rendered fine, copy the url from your terminal log and paste it into your browser (I recommend Firefox). This url usually looks something like this `http://127.0.0.1:4000/dh-in-prison`. At this point you should be looking at your own working version of DH in Prison, served from your computer without the internet.

If you had errors that you could not resolve, follow the installation instructions in the [documentation of Ed](https://elotroalex.github.io/ed/documentation/), replacing "ed" with "dh-in-prison" whenever necessary. Ed. is the Jekyll theme that DH in Prison is built with, so if what you want to do is completely changing the content of DH in Prison to build your own site, I strongly recommend you clone Ed instead and use that to build your site because Ed's documentation is much better than mine.

If you are interested in talking about, contributing to or otherwise getting involved in the DH in Prison project, see its sibling site [Intro to DH](https://binipringle.github.io/intro-to-dh/) and write to me at springle@ccny.cuny.edu or https://github.com/binipringle  

---
