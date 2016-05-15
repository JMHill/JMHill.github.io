---
project: justinmhill
tag: portfolio
priority: 1
---

My personal website is built on jekyll and hosted via the GitHub "user pages" functionality. GitHub is kind enough to provide every user with their own personal subdomain, in the format username.github.io. If you're interested in creating a simple jekyll-based page for an individual project, that capability exists as well. You can read more about it here: [https://pages.github.com/](https://pages.github.com/).

Jekyll is a "simple, blog-aware, static site generator." Basically, jekyll is a ruby program that takes a bunch of markdown and layout files, generates the necessary html files, and places them in the correct public directory structure for your site to be served. You can check out jekyll's quickstart guide [here](https://jekyllrb.com/docs/quickstart/), or their guide on getting up and running with GitHub pages [here](https://jekyllrb.com/docs/github-pages/).

For styles, I borrowed and adapted the sample blog layout from the folks over at [Pure.css](http://purecss.io/). Pure is a nice and simple set of css modules that provides a very intuitive responsive grid system.

In addition to just providing a spot for me to blog and talk about my projects, I'm treating this site as a good platform for tinkering with the [Liquid templating engine](https://docs.shopify.com/themes/liquid/basics), created by Shopify and used by jekyll to handle all of your layout and control-flow needs.

So far, I've had a lot of fun using jekyll for my personal website needs. I keep all of my project metadata in a simple JSON file, and then write up summaries (like the one you're reading right now) as markdown files in a jekyll collection. Then, jekyll outputs an individual project detail page for each project, pulling in the metadata to provide the information above, and injecting this summary.

I highly recommend jekyll, especially if you're a newer programmer like me - it's been a much more fulfilling learning experience than using a traditional content management system.
