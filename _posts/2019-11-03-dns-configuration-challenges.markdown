---
layout: post
title:  "DNS Configuration Challenges"
date:   2019-11-03 12:49:17 -1000
---
>Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical internet end-users.

## Reason 1
Intimidation! People who live "near" the technical world have heard of DNS and know that DNS problems can break everything.  DNS has its own vocabulary.  The documentation does not always make the connection between the concepts the end-user knows and the configuration steps.  For example, I understand my site has a URL that DNS will map to an IP address but what are those different record types?  

## Reason 2
Some aspects of DNS are just complex.  For example, if you make a DNS change, you may not be able to immediately confirm that it worked.  Factors include the DNS cache and the change needs to propagate through the network of DNS servers.

## Some Thoughts  
A good question to ask is *why do less technical end users need to configure DNS?*  

For these users, it is important to design a user interface that corresponds to their needs and technical understanding.  Good user interfaces are intuitive (supplemented by minimal documentation) and make it difficult for users to do harm.  

Obviously, all DNS configuration options would not be accessible through this type of interface. For users with deeper technical understanding of DNS, a more robust interface to DNS configuration can be provided.
 