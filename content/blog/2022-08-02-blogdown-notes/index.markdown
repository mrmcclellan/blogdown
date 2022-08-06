---
title: Notes to self on blogdown
author: Matthew McClellan
date: '2022-08-02'
slug: []
categories: [rmarkdown, meta]
tags: [rmarkdown, meta]
excerpt: As I learn how to use - and not use - blogdown, I'll update this post.
summary: summary
---

As I learn how to use - and not use - blogdown, I'll update this post.

## Lessons

Don't create posts using the "new post" addin! The presence of posts created via addin causes a strange error in the blogdown::serve_site() command, preventing live preview on localhost. The build_site() command still appears to work fine. Deleting any posts created via addin allows serve_site() to work again. Create all posts using blogdown::new_post().

## Resources

Documentation, tutorials, etc.

- [Hugo Apero documentation](https://hugo-apero-docs.netlify.app/)
- [Up & Running with Blogdown in 2021]
- [Alison Hill walks through "Up & Running"](https://www.youtube.com/watch?v=yXFu_upDL2o)
- [Happy Git and GitHub for the useR](https://happygitwithr.com)
- [blogdown: Creating Websites with R Markdown](https://bookdown.org/yihui/blogdown/)
