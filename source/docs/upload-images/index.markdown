---
layout: page
title: "Uploading Images: GitHub Tricks"
date: 2015-11-17 20:34
comments: false
sidebar: false
socialite: false
footer: false
---

### GitHub Asset Management

Github does not currently provide an asset management tool for developers repositories. But GitHub DOES have a hidden feature that can be used as a CDN for assets (images, attachements, etc). it’s called the Issues feature!

Smart use of Issues makes it super easy to uploaded files that are associated with your repository… and these files not part of its commit/change processes. If you create an Issue within your repository, you can drag-n-drop files to the issue comments to automatically upload and attach static content to your repository.

Here are samples steps:

#### Step 1) Click on Issues tab:

Create an issue with title appropriate to the context of your images

{% img /images/GitHubTricks_1.png %}

#### Step 2) Create a new issue

In the samples below, I am uploading images that will be used within the 2015-11-08-about-junk-professionals.markdown document, so I will create an issue title: Images for 2015-11-08-about-junk-professionals.markdown. Notice the instructions on the bottom of the Write tab? You can drag-n-drop 1 or more images onto the Leave a Comment box and those files will be instantly uploaded to the hidden GitHub asset manager.

{% img /images/GitHubTricks_2.png %}

After each upload, GitHub will update the text the markdown link to the image

{% img /images/GitHubTricks_3.png %}

#### Step 3) Using uploading images or assets (e.g. PDF, SWF, etc)

After your submit the new issue, you will be able see recently attached image(s) rendered correctly. And finally, you can copy the URL with a right-click on the image

{% img /images/GitHubTricks_5.png %}
{% img /images/GitHubTricks_6.png %}

You can add more images to an issue at any time. Best of all, these images can now be referenced in 2015-11-08-about-junk-professionals.markdown and the post pages [using the link URL].
