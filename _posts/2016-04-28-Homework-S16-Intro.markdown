---
layout: post
title:  "Homework Assignments"
date:   2016-04-28 08:50:13 -0700
categories: hwk S16 CS20
---



For various reasons, I'm experimenting with a new way of publishing homework assignments to the web.  (See more on my reasons, below.)  The new site is here: [https://UCSB-CMPTGCS20-S16.github.io](https://UCSB-CMPTGCS20-S16.github.io)

H00 is still on the old Mediawiki site for now, but if all goes well, H01 and future homeworks will be published here.


* H00: as [html](https://foo.cs.ucsb.edu/8wiki/index.php/S16:Homework:H00), and as [pdf](http://www.cs.ucsb.edu/~pconrad/cs20/16S/pdf/cs20-S16-H00.pdf)


Reasons I'm switching
---------------------

I used to use the same software that is used for Wikipedia (called "Mediawiki"), but it is turning out to be a bit of a software maintenance burden.   It's also harder to share materials with other instructors.  My hope is that using something based on github will make that easier.   This platform, Jekyll, can be run on github.com's infrastructure at no cost (for public sites), or run on our own infrastructure.    It uses git for version control.   The syntax is straightforward (unlike hand coded HTML.)

The Source Code
---------------

The source code for this site is in the github repo: [https://github.com/UCSB-CMPTGCS20-S16/UCSB-CMPTGCS20-S16.github.io](https://github.com/UCSB-CMPTGCS20-S16/UCSB-CMPTGCS20-S16.github.io)  

Maintaining a Course Website this way is easy
---------------------------------------------

The number of files in this repo may make it seem as if there is a tough learning curve to maintaining a site with Jekyll on github pages.  Fortunately, that's not the case.

Creating new pages on the site is as simple as adding new files in the directory `_posts` in this repo.   It can be done directly in the github.com website interface, so no actual knowledge of github or jekyll is required&mdash;it is sufficient to know:

* which directory to edit pages in (viz: `_posts`)
* what the naming convention is for new pages (and the example is easy to follow)
* how to use Markdown (which is a straightforward and intuitive format learnable in 5 minutes)

There is no "database" to maintain, since Jekyll works from static files only.      All state for the site is maintained in the github repo, and all history of edits is maintained by git.

