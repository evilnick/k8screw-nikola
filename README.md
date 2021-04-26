# k8screw-nikola


Some quick hacks -


check out this (main) branch to make a post. Then in the directory:

./newpost creates a new post from the template and gives you a filename - edit this to make your post
./publish rebuilds the site and builds the `blog` branch 

OR, you can just add a new markdown file to the 'posts' directory. It will need to have the relevant frontmatter:

```
---
category: ''
date: 2021-04-15 14:30:29 UTC+01:00
description: ''
link: ''
slug: a-name-for-the-post
tags: ''
title: markdown
type: text
---
```

The output in blog is rendered by GH pages here - <https://evilnick.github.io/k8screw-nikola/>
