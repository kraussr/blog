---
layout: blog
title: Serverless github authentication working
date: 2019-06-16T12:05:01.729Z
categories:
  - news
  - blog
---
As usual, the problem was in the minor details... 

{{< gist 54b452c1ce60eb884530b0c4031348d8 >}}

The `base_url` _must_ be the server name of the serverless function and the auth_endpoint must be the complete path to the function.

But now we're good to go!
