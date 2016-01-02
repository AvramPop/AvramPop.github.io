+++
categories = ["misc"]
date = "2015-12-31T14:10:41+02:00"
title = "How to setup a blog using Hugo?"

+++

This is my first post on the site.  I hope that you like it!

If you do not understand, https://www.digitalocean.com/community/tutorials/how-to-install-and-use-hugo-a-static-site-generator-on-ubuntu-14-04 is available for you. I lerned the basics from there, too.

## #1

Download your suitable distribution of Hugo from https://github.com/spf13/hugo/releases. Create a new directory named Hugo. Inside of it, a subdir, called "bin". Extract what you've downloaded there. In the same parent folder, make another directory named "Sites".

## #2

Open a shell terminal, and write down "$ cd ~PATH_to_your_HUGO_directory". Hit enter. This will lead you to Hugo headquarters:)

## #3

In shell, write "$ hugo new site firstSite". This will create a new site called "firstSite". Navigate to the site with "$ cd ~PATH_to_your_FIRSTSITE_directory".(It is a subdir of sites -> Hugo)

## #4

Basically, the site exists in this moment. We will create 2 pages, a "About me" page, and one main post page, called "My first post".
So write down in shell:
	1. "$ hugo new about.md"
	2. "$ hugo new post/My-Fisrt-Post.md"

## #5

Navigate with explorer to about.ml. Open it with your favourite text editor. Under the second "+++" sign, you can write whatever you want so see in your site.

## #6

Navigate to my-first-post. There, you can do the same like #5. Save all the things you've changed, and get back to shell.

## #7

"$ hugo server" -> Enter. Then rock with Hugo at "localhost:1313" using your browser :)

