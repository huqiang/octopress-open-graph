octopress-open-graph
====================

A plugin to generate og meta tags for octopress powered site

## How to use it?
1. download `og.html` and put it in `source/_includes/custom/`

2. add 
```
{% include custom/og.html %}
```
in `include/custom/head.html`

## set cover image for site and post
add
```
cover: PATH_TO_IMAGE
```
in `_config.yml` for site, and in post header for posts.