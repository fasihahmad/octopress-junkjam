---
layout: page
title: "Contributing JunkJam"
date: 2016-05-25 03:30
comments: false
sidebar: false
footer: false
socialite: false
---


Add new markdown file to start writing, blogging at its finest steps.

1. Add **New File** in [JunkJam repo](https://github.com/junkjam/cms.blog.junkjam.in/tree/master/source/_posts) to fork this project and **Propose new file**.

2. **Create pull request** to get merged and published your markdown file.

##  Propose new file

Name your file according to below naming convention in [source/_posts](https://github.com/junkjam/cms.blog.junkjam.in/tree/master/source/_posts) directory:

**YYYY-MM-DD-post-slug.markdown**

The name of the file will be used as the url slug, and the date helps with file distinction and determines the sorting order for post loops
**Edit new file** and add a block of yaml text
which tells JunkJam how to processes posts. e.g. [post](https://github.com/junkjam/cms.blog.junkjam.in/edit/master/source/_posts/2015-11-08-about-junk-professionals.markdown)

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

## Blogging Basics

* Markdown basics for writing.  ([Writing](https://help.github.com/articles/basic-writing-and-formatting-syntax/))

* JunkJam basics for image.  ([Image](how-to-add-images-in-post/))

* Upload Images for post.  ([Upload](how-to-upload-images-for-post/))

* Online Markdown Editor. ([Editor](http://dillinger.io/))

