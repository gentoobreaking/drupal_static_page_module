Drupal install tome module for making static pages

---
title: 'Drupal install tome module for making static pages'
disqus: hackmd
---

Drupal install tome module for making static pages
===
![downloads](https://img.shields.io/github/downloads/atom/atom/total.svg)
![build](https://img.shields.io/appveyor/ci/:user/:repo.svg)
![chat](https://img.shields.io/discord/:serverId.svg)

## Table of Contents

[TOC]

## Operator Guide

User story
---

Step.1 Find one module in drupal website
---

https://www.drupal.org/project/tome
And then you need to copy this URL at "Download" part.
Like this: https://ftp.drupal.org/files/projects/tome-8.x-1.4.tar.gz

Step.2 Install one module in drupal website
---

Go "Manage" -> Extend -> List -> Install new module
![drupal_install_tome_module](https://github.com/gentoobreaking/drupal_static_page_module/blob/main/pics/drupal_install_tome_module.png)

Paste the URL from Step.1.
```gherkin=
https://ftp.drupal.org/files/projects/tome-8.x-1.4.tar.gz
```
![drupal_static_page_base_url](https://github.com/gentoobreaking/drupal_static_page_module/blob/main/pics/drupal_static_page_base_url.png)


Step.3 Tome module function list
---

![drupal_tome_module_list](https://github.com/gentoobreaking/drupal_static_page_module/blob/main/pics/drupal_tome_module_list.png)


Step.4 Generating these static pages with Tome module
---

Click "Generate static site", and then input the base url with original website from drupal.
At this pharse, you could configure the output folder place.
![drupal_static_page_base_url](https://github.com/gentoobreaking/drupal_static_page_module/blob/main/pics/drupal_static_page_base_url.png)

![drupal_static_page_generating](https://github.com/gentoobreaking/drupal_static_page_module/blob/main/pics/drupal_static_page_generating.png)
And then you could get the static pages at the folder that you configured before. Or just download from here.


