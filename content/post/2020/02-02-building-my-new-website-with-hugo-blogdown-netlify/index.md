---
authors:
- admin
categories:
- Resources
date: "2020-02-02T15:00:00Z"
draft: true
featured: false
image:
  caption: ""
  focal_point: ""
  placement: ""
  preview_only: false
lastmod: "2020-02-02T15:00:00Z"
projects: []
subtitle:
summary:
tags:
- GitHub
- Hugo
- Netlify
- R
- RStudio
- static site generation
title: 'Rebuilding my new website with Hugo, R blogdown, GitHub, and Netlify.'
---
I have been rebuilding my personal website using a static site generator, first, because I wanted a cleaner and streamlined site with an easy upkeep, plus I was motivated to learn the new tools, and more importantly, to move away from hosting on Wordpress due to the really annoying ads. The process was on and off, and although I found tips online that you can indeed complete it in a day or less, I only found time to on it very intermittently, mostly while in transit at airport terminals and during flights and over weekends, which was why it took about three months to deploy the site—and only last night, finally! The website is still incomplete and still under reconstruction, with most of my old blog posts and pages from my old 14n121e website to be slowly incorporated in my new website slowly.

Below, I have put together some guidance on how I built my new website, which you may find helpful in case you were wondering how you could go about building one for yourself too. I tried to put together the major steps with as much detail as I can recall, albeit I may have missed minor ones.

**Prerequisites**

After some prior searching online, I settled on using Hugo, R blogdown, GitHub, and Netlify as the combination of tools/resources I would employ for setting up and rebuilding my website. Note that I did not mind reconstructing the site manually (e.g., migrating contents such as blog post one by one) because it was not alot and also so I could understand the inner workings, hence I did not pursue (semi-)automated ways that existed for migrating content from Wordpress to the new site. To get started, I ensured the following online accounts were set up and the software tools were installed in my Mac OSX machine:

- [Git](https://git-scm.com) and a [GitHub](https://github.com) account as the version control system for tracking the changes in a dedicated repository containing the website contents; 

- [R](https://cran.r-project.org) and [RStudio](https://rstudio.com), the premier IDE for R, plus the [blogdown](https://bookdown.org/yihui/blogdown/) R package developed by [Yihue Xie](https://yihui.org/en/);

- Then, [Hugo](https://gohugo.io), an open-source static site generator for building websites, plus the [Academic](https://themes.gohugo.io/academic/) Hugo theme by [George Cushen](https://georgecushen.com), of which was my personal choice as the theme for creating a simple and customisable website using the [Markdown](https://daringfireball.net/projects/markdown/) markup language (and it is apt for academics/scientists/researchers); 

- In addition, I used some advanced features including [Disqus](https://disqus.com) to enable comments and discussions, and [Google Analytics](https://marketingplatform.google.com/about/analytics/) to understand my website traffic; and

- Finally, a [Netlify](https://www.netlify.com) account to enable a fast and continuous deployment of the website, once the GitHub repository was connected and the build settings were added.

For most of the above, I already had prexisting registered accounts and had installed the tools, except for Netlify (so I had to sign up for a new account) and R blogdown and Hugo (both of which I had to newly install).

1. Creating a repository on Github 

2. Installing blogdown, Hugo and the Academic theme



As a final note, I have to say that the initial setup required some effort and time to learn a few new tools—and troubleshoot as required—but in the end, I was satisfied with the process and the outcome, and also from knowing that from here on the upkeep required to maintain my online presence would be minimal.  


***Acknowledgements***

I used several resources online including 

instructions of how to use Hugo, blogdown, and Netlify

helpful and easy-to-follow instructions form
Yihue Xie for blogdown
George Cushen for the Academic theme for Hugo 

plus blog posts by XXX

Katie Scanton


Erika Fille Legara
Zhi Yang

I referred to their posts, and sometimes even the GitHub-hosted repositories hosting their sites, as well as finding many bits of inspiration from the bespoke designs of their own websites 

was really helpful 


Special thanks to Lloyd Zapanta for developing a true type font for the Baybayin script, which is the indigenous alphabet writing script of pre-colonial Philippines. He designed several true type fonts of the Baybayin script, of which I particularly used Baybayin Sisil rendition for creating my website logo, which is essentially my name written with Baybayin characters.





