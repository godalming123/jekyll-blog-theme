# jekyll-blog-theme
A jekyll theme for creating blogs with categorys. It doesn't need any JS, is extremely fast and has a bold design.
You can preview the theme [here](https://godalming123.github.io/jekyll-blog/) and the source code is [here](https://github.com/godalming123/jekyll-blog).
## Usage
Copy over all of the files from the theme (except for readme.md), and add a `_config.yml` file:
```yaml
title: "Some title"
description: "Add a description here"
icon: "Add a path to an icon in here"
```
Then create your posts for example `category_of_post/_posts/2023-06-23-example-post`:
```markdown
---
layout: post
---

This is a simple example post in markdown.
```
## TODO:
 - add coloring to code blocks
 - small refinements in the design, typography, ETC:
    - tables need better styling
 - Requires JS so would like to do but not implementing:
    - a full screen image view (requires JS)
    - copy button for code blocks (can only be done with JS so I am not implementing)
## DONE:
 - 404 page - maybe just change the spacing between 404 and the text
 - home page
 - posts page
