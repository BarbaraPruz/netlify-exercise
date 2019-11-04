---
layout: post
title:  "About Making This Site"
date:   2019-11-03 12:52:17 -1000
categories: jekyll update
---
> Talk about how you made your site and why you chose the tools you did.  Briefly explain a challenge you experienced in setting up this site and how you solved it.

## The Plan

1. Selecting a Static Site Generator: I don't really know any static site generators and so I'll use this exercise as an opportunity to learn something new.  Since  they seem like two of the most popular, I decided on either Jekyll or Gatsby.  
2. I like to see things working and know that all the pieces will fit together.  So I'll create skeleton site and deploy to Netlify.  The posts will just be placeholders.  At this point, I don't care about content or styling. This is just to verify 'end to end' functionality.
3. The real stuff! Work on content for posts.  Incrementally, add site content and push to Git.  During this step, possibly do some minor site styling.
4. Final review of answers and submission.
5. Optional: Review styling focusing first on anything that may distract from content. Other considerations are styling changes to make content more informative or interesting.  A theme change (from Minima to something like Clean Blog) might make sense.  While working these styling changes, use a Git branch and merge to Master when complete.

## What Happened
1. For Jekyll, I easily found a reasonably good series of tutorial videos on YouTube: [Mike Dane Jekyll Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB).  In less than 30 minutes, I felt confident that I could use Jekyll to complete the exercise.
2. I set up skeleton site with a Git repository.  One small problem:
- Being a blog theme, the posts are displayed in reverse chronological order.   I manipulated the 'front matter' post dates to get the order that I wanted.
3. Deploy to Netlify: As I had previously deployed a GitHub repository to Netlify, I knew it was easy.   I googled to see if there were special considerations related to Jekyll and found a related post: [Step by Step Guide for Jekyll 3.0 on Netlify](https://www.netlify.com/blog/2015/10/28/a-step-by-step-guide-jekyll-3.0-on-netlify/). Setting up the deployment was not a problem but I had a build error!  Steps to resolve:
- I reviewed the Deploy Log and saw an error - something about the Ruby bundler version. 
- I google the error message. I found some information that led me to [ GitHub Netlify Build Image Issue 296](https://github.com/netlify/build-image/issues/296). Though the issue is labeled merged, it doesn't seem to be in production. In the discussion, a workaround is described.
- I applied the workaround (removing some lines from gemfile.lock) and pushed the change to GitHub.
Build succeeded! 
4. Added content (with some minor styling changes) to site periodically pushing to GitHub. This was a fun step!
5. After taking a little break, I reviewed content again with fresh eyes and made some small changes.

Good to Go! (To come: V2.0 with better styling.)

