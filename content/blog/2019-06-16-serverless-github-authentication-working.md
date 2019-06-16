---
layout: blog
title: Serverless github authentication working
date: 2019-06-16T12:05:01.729Z
categories:
  - news
  - blog
---
As usual, the problem was in the minor details... 

```
backend:   name: github     repo: kraussr/blog   base_url: https://jr0ahwavzf.execute-api.eu-central-1.amazonaws.com     auth_endpoint: /prod/authsite_id: kraussr.github.io
```

The `base_url` _must_ be the server name of the serverless function and the auth_endpoint must be the complete path to the function.

But now we're good to go!
