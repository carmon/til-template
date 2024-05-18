til-template
============

This is the template repository for a blog.

## How does it work

## /creator

Creator takes a `dates.json` (repo comes with an example) and recreates the posts with order of date, this 
date is usually the date of the commit of the markdown file added to `blog/posts/`.

`sh ./scripts/build.sh` installs and runs the nodejs app 

## /blog

Contains the rendered `index.html` reading the markdown files.

`sh ./scripts/local-run.sh` renders a webserver with the contents of `blog/` folder. 
