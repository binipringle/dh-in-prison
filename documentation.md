---
layout: page
title: Documentation
author: Sabina Pringle
source: Ed documentation by Alex Gil
---

This is a static site built with Jekyll using [Ed](https://elotroalex.github.io/ed/).

### To make a copy of this site and run it on your computer:

You will need to use your terminal. If you don't remember much about how to use your terminal, I recommend "[Introduction to the Command Line](https://github.com/GC-DRI/command-line)."

### Once you are in your terminal, first try the "easy" or "lucky" way to install:

Create a folder in your Desktop where you want your copy of this site and navigate into that folder.

Now type or paste the following commands:

~~~ bash
$ git clone https://github.com/binipringle/dh-in-prison.git
$ cd dh-in-prison
$ gem install bundler
$ bundle install
~~~

Done! To see if DH in Prison is working properly, tell Jekyll to serve by typing

~~~ bash
$ jekyll serve
~~~

If the site was rendered, copy the url from your terminal log and paste it into your browser (my preference is Firefox). This url usually looks something like this `http://127.0.0.1:4000/dh-in-prison`. Now you should be looking at your own working version of DH in Prison, served from your computer without relying on the internet.

### If the site did not render:

And you had errors you could not resolve, follow the installation instructions in the [Ed documentation](https://elotroalex.github.io/ed/documentation/), replacing "ed" with "dh-in-prison" wherever necessary. Ed is the Jekyll theme that I used to build DH in Prison, so if you clone DH in Prison onto your computer and run into issues, I recommend looking to the [Ed documentation](https://elotroalex.github.io/ed/documentation/) for help.

## Note on adding images

In order to render images, I added the following code to the **_config.yml** file:

```
defaults:
  - scope:
      path: "assets/img"
    values:
      image: true
```

I enabled responsiveness on mobile devices in the following line in the **_ed.scss** file:

```
<meta name="viewport" content="width=device-width,initial-scale=1.0,shrink-to-fit=yes" />
```

## Note on adding licenses

Because the logo, illustrations and some texts on this site are distributed with different licenses, I created folders for collections and put a copy of the pertinent license in that folder in a LICENSE.md file. I added the text of this CC BY-NC-SA 4.0 license CC and the text of the CC BY-SA 4.0 which my work and the GCDRI and GC DHRI work are licensed with, to the MIT License which Ed is licensed with in the LICENSE.md folder at the top level of the repository.
