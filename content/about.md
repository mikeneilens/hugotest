---
title: "About"
date: 2020-05-06T18:41:26+01:00
authorbox: false
menu: 
  main:
    weight: 10
sidebar: "right" # Enable sidebar (on the right side) per page
widgets: # Enable sidebar widgets in given order per page
  - "recent"
  - "taglist"
  - "categories"
---

This is a demo of how [hugo](https://gohugo.io) can be used to create a static site containing information about the Technical profession.
<!--more-->
Pages are added to the site by adding new <name>.md files to /content/post. The content consists of a header containing metadata for the page and content written using mark down format. Mark down allows the content to be nicely formatted without being as complex as raw HTML.

The metadata can include taxonomy information such as what categories the page belongs to or tags. You can attach pages to the main menu and configure whether you want to show a side menu and what content to show in the side menu (e.g. search bar, lists of categories, list of tags)

I've set some categories to appear on the menu bar. If new categories are added to pages as metadata they will be listed on the site under directory /categories/ automatically. Tags are listed automatically on the site under directory /tags/.

Hugo allows themes to control how the content is laid out. This project uses [mainroad](https://themes.gohugo.io/mainroad/) theme.

In this demo the hugo project is stored in github and deployed using a guthub site. To test changes locally, install hugo and clone the repo. You can the run the site locally by entering `hugo server` when in the directory containing the config.toml file (root of the project in this case). 


