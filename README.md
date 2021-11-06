# Minimal blog for Github Pages

This is a minimalist blog repository, for Github Pages, with a search feature (thank to [lunr.js](https://lunrjs.com/)) on the pages and articles titles, categories, and tags. The theme is [minima](https://github.com/jekyll/minima), the default [Jekyll](https://jekyllrb.com/) theme.

Look at the file _config.yml to configure your blog.

There is a page that lists all the categories, and a page that lists all the tags (this one is optional : look at the _config.yml to enable or disable it).

## How to convert your repository to Github Pages

To convert this repository to a Github Pages blog, go to Settings, and click on "Pages" :

![image](https://raw.githubusercontent.com/brahimmachkouri/images/main/settings.png)

Click on "main" in the dropbox and Save to finish :

![image](https://raw.githubusercontent.com/brahimmachkouri/images/main/settings_ghpages2.png)

## How to create to create a new post

To create a new post, create new file in the _posts folder, it should be named as a date followed by post title, with words separated by dashes, for example: “2021-11-05-upgrade-zalman-firmware-to-iodd.md”.

![image](https://raw.githubusercontent.com/brahimmachkouri/images/main/gh_create_new_file.png)

![image](https://raw.githubusercontent.com/brahimmachkouri/images/main/gh_create_new_file2.png)

The ["Front Matter"](https://jekyllrb.com/docs/front-matter/) block (example below) is needed before clicking on the commit button :
```
---
layout: post
date: 2021-11-05 11:29:00
title: Upgrade Zalman VE-300 firmware to an iodd 2531 firmware
category: materiel
tags: zalman iodd firmware
---
```
date: date of the post\
title: the title you want for your post \
category: what category the post belongs to \
tags : keywords to easily find the post with a search

Then wait for about 1 minute or 2, then go to your blog homepage. (It should be https://yourusername.github.io/repositoryname/)

## Note

If you rename your repository (in Settings), don't forget to edit the _config.yml file in order to modify the baseurl variable also.
