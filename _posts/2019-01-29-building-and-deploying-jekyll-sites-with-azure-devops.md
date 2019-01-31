---
layout: post
title: 'Building and Deploying Jekyll Sites with Azure DevOps and Azure Storage Static Site Hosting'
tags: [AzureDevOps, CICD]
featured_image_thumbnail: /assets/images/posts/2019/jekyll-build/header_thumb.jpg
featured_image: /assets/images/posts/2019/jekyll-build/header.jpg
---

When I decided to get back into blogging after having ditched my previous effort a few years back, I had two initial thoughts.  First, I wanted to take a look at options were available for blogging platforms.  Second, I wanted to start my post off with something more interesting than the obligatory "here's how I built my blog" post.  Well, as of this post, I'm 1 for 1 in those goals as I'm about to run you through how I'm deploying and hosting my shiny new blog using <a href="https://jekyllrb.com/" target="_blank">Jekyll</a>, <a href="https://azure.microsoft.com/en-us/services/devops/" target="_blank">Azure DevOps</a> and <a href="https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website" target="_blank">Azure Static Website Hosting</a>.