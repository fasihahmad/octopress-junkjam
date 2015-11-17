---
layout: page
title: "Contributing JunkJam"
date: 2015-11-17 19:30
comments: false
sidebar: false
footer: false
socialite: false
---


Add new markdown file to start writing, blogging at its finest.

Click + icon on [JunkJam repo](https://github.com/fasihahmad/octopress-junkjam/tree/master/source/_posts) to fork this project and create a new markdown file.

Create Pull Request to get merged and published your markdown file.

## Blogging Basics

* Markdown basics for writing.  ([Writing](https://help.github.com/articles/markdown-basics/))

* JunkJam basics for image.  ([Image]({{ root_url }}/docs/image-tag/))

* Online Markdown Editor. ([Editor](http://dillinger.io/))

Blog posts must be stored in the source/_posts directory and named according to naming conventions:

**YYYY-MM-DD-post-slug.markdown**. The name of the file will be used as the url slug, and the date helps with file distinction and determines the sorting order for post loops


Open a post in editor and you'll have to add a block of yaml text
which tells JunkJam how to processes posts.

``` yaml
---
layout: post
title: "Junk Professionals, What the Fu**"
date: 2015-11-08 23:18:49 +0530
comments: true
categories: JunkJam
---
```

Here you can turn comments off or add categories to your post. JunkJam works on a multi-author blog, you can add `author: Your Name` to the
metadata for proper attribution on a post. If you are working on a draft, you can add `published: false` to prevent it from being posted when you generate your blog.

You can add a single category or multiple categories like this.

``` yaml
# One category
categories: JunkJam

# Multiple categories example 1
categories: [Urban Warrior, Platform Heel, Miami Calling]

# Multiple categories example 2
categories:
- Urban Warrior
- Platform Heel
- Miami Calling
```




