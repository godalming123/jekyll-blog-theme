# jekyll-blog
A jekyll theme for creating blogs with categorys. It doesn't need any JS, is extremely fast and has a bold design.
## Usage (only on GH pages)
Add this to your `_config.yml`
```yaml
remote_theme: "godalming123/jekyll-blog-theme"
title: "Example blog"
description: "Add a short descriptino of your blog here"
icon: "(Optional) add a path to an icon here"
```
Then add the following
`index.html`
```html
---
layout: home
---
```
## TODO:
 - add coloring to code blocks
 - small refinements in the design, typography, ETC:
    - tables need better styling
 - a full screen image view (requires JS)
 - copy button for code blocks (can only be done with JS so I am not implementing)
## DONE:
 - 404 page - maybe just change the spacing between 404 and the text
 - home page
 - posts page