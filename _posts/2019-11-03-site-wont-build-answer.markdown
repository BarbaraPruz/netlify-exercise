---
layout: post
title:  "Site Won't Build Answer"
date:   2019-11-03 12:48:17 -1000
---
>A customer writes in saying their “site won’t build”.  Compose:
your best short (2-paragraph) customer-facing answer, 
without any additional data, 
that could be useful in the generic case, 
but would also lead to a customer providing a more actionable response.

Sorry to hear about your problems.  Build errors are common but often easy to fix. To start,
- Confirm site builds and runs correctly in local environment.
- Check the deploy log to determine the exact error.
    - Note: if using the CLI, the following command shows build details    
    <span style="font-family: Courier">DEBUG=* netlify deploy</span>

If the error is not something that you recognize, check the [Build Troubleshooting Tips]("https://docs.netlify.com/configure-builds/troubleshooting-tips/").  

If you still cannot determine the cause of the error, please provide
- site settings
- deploy log  

and we can help review.
