---
title: "Hello, World!"
date: 2020-07-25T16:24:31+08:00
draft: false
toc: false
images:
tags:
  - personal
---

## Welcome

Hello? Is this thing on? Good. Welcome to my tech blog. Here you will find all sorts of stuff that I've found interesting while working as a consultant and developer for cloud infrastructure and automation, with an eye for security & compliance concerns at scale.

I also blog about stuff that I find interesting, strictly within the tech space. So that includes side-projects and whatnot.

**Disclaimer:** All content here are my opinions alone, and do not formally represent those of my employers - past, present, or future.

## Who Am I?

Follow the links to find out more:

* https://scott.maclure.info/cv/
* https://www.linkedin.com/in/scott-maclure/
* https://github.com/ScottMaclure/

## How did I set this blog up?

Let's start with some desired outcomes:

* Keep it simple - strip back the end-end worklow to minimise moving parts.
* It's gotta be "almost-free" to host...
* AND there won't be any spikes in cost (beware free tiers in Cloud providers!)
* Its easy to author
* I can setup a minimalistic css theme without much effort
* It has tagging support
* I don't care about authoring from mobile - desktop|laptop will be fine.

My solution:

* The maclure.info domain I had already registered via Amazon's Route 53 service. So I'll use R53 to manage DNS.
* The code for most of my projects are hosted on github, which has support for "[pages](https://pages.github.com/)", which is (free) static hosting, AND custom domain names are supported. Perfect.
* [Hugo](https://gohugo.io/) is a static site generator I've used in the past, seems decent and fast, with some nice themes. That means I can locally compile, removing the need for an external build server.

The end result is that I can do the following:

* I can run a local server and preview my drafts
* I can commit and push drafts up to github without changing the deployed site content
* I can configure Hugo to build the static site into /docs subfolder, which is compatible with github's hosting
* I can "publish" content by setting "draft: false" in the metadata, running the "hugo" binary, then git commit & git push
* I maintain zero-infrastructure! Well, I manage a domain, that's it.

## What's next?

Over time I will write and publish blog posts focused around whatever I'm learning or playing with at the time.

This will mostly be for my learning benefit, as I find being able to write about a topic in a manner that explains it to someone else _really_ helps me to internalise my own understanding of the content.

So yeah, this blog is mainly for me, but written for public consumption also.

Welcome.
