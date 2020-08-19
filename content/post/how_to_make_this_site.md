---
title: "How_to_make_this_site"
date: 2020-06-27T14:37:48+05:30
Description: ""
Tags: []
Categories: []
DisableComments: false
---
---

### This site is build using [HUGO](https://gohugo.io/), a static site genarator with its [Template](https://themes.gohugo.io/anatole/) and hosted on github.

---
## Required
Installation

* [HUGO](https://gohugo.io/)
* [Git](https://git-scm.com/downloads)

## After installation
## Start a project:
        hugo new site <site-name>
    
## For initialising a empty git repo
    cd <site-name>
    git init

## For using a template
Download a theme as a git-submodule from [Hugo Themes](https://themes.gohugo.io/)

### For Downloading as a git-submodule

    git submodule add <theme git-reposotory link> themes/<theme-name>

### Adding the theme to the config.toml file

For this you can reffer the example site

        <site-name>/themes/<theme-name>/example-site

Or copy the example site

     cp themes/<theme-name>/exampleSite/* . -r

After copying the example site modify the changes as per your need.

### For adding new post

    hugo new post/<post-name.md>

### For running the site on localhost

    hugo server

## Hosting and Deploying The site

Reffer [HUGO hosting](https://gohugo.io/hosting-and-deployment/)

After you build the site type the command

    Hugo


