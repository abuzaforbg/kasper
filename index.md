---
layout: home
title: "Octopress 3.0 Is Coming"
date:   2020-08-07 10:18:00
categories: Thriller Comedy Horror
---

The way Octopress is being distributed and maintained is nearing its end. There are many things I've always disliked about how Octopress works. So before I talk about the exciting part, I'd like to tell you what's wrong with Octopress.

What's wrong?
If I'm being harsh, I'll tell you that as it is now, Octopress is basically some guy's Jekyll blog you can fork and modify. The first, and most obvious flaw, is that Octopress is distributed through Git. I want to punch through a wall when I think about users wrestling with merge conflicts from updating their sites. It’s absurd.

Octopress is released as a single product, but it's a collection of plugins and configurations which are hard to disentangle. if you want to change or remove anything you're leaving the "golden path" and updates will be painful, if not impossible — short of copy and paste. Even I can't remove things from Octopress. If I want to stop maintaining a plugin it will also disappear for anyone who updates. While some have suggested using Git tags as a kind of steam-punk versioning, that simply will not solve the real problem. This isn't how software products should be distributed. Git is for collaborators; not users.

Then there are the themes. I planned to create a system for distributing themes independently from Octopress, but I hadn’t solved it when I released 2.0. Even then, I've come across quite a few websites with Octopress theme galleries. While there are some nice ones, they are all distributed through git and installed with an ill-conceived rake task that was never meant to be used for this. All of this is a constant reminder that many people are spending time building on my mistakes.
