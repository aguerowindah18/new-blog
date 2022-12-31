---
title: How this site was born 👶
date: 2022-12-31 19:44:00 +08:00
modified: 2022-12-31 19:44:00 +08:00
tags: [blog, vercel, jekyll, github]
description: All the services are free, a source code this site placed on github repository and intergration with vercel service, another service that you can use is github page for hosting your own static site.
---

The website was made using Jekyll the one of open source static sites generator, and using my own simple theme, the creator called [klisé](https://github.com/piharpi/klise).

<hr>

All the services are free, source code the site was placed on [github](https://github.com/piharpi/mahendrata.now.sh) repository and intergration with ~~[vercel](https://verel.app)~~ service, another service that you can use is [github page](https://pages.github.com/) for hosting your own static site.

<hr>

#### Let's do this

So, before we start create a site, you need some tools, you can self paced for how to installing each tools, on this guide i'm just want to show you how to install jekyll and deploying in vercel, but make sure you have each tools below.

#### Prerequisites

Requirements before we doing magic show.

- [Ruby](https://www.ruby-lang.org/en/downloads/) programming language
- [Git](https://git-scm.com) (version control)
- [Vercel](https://vercel.com) and [Github](https://github.com) account
- [Bundler](https://bundler.io)

#### Installation

First, you need some [SSG](https://www.staticgen.com/), there are many kind ssg, but in case i'm using Jekyll cause i'm already familiar with it, open your terminal and type command on below

```bash
$ bundle install jekyll # installing jekyll in your machine
$ jekyll new my-site && cd my-site # create new jekyll project
$ jekyll s # run jekyll server
```

Now, jekyll is running on your local machine, open your browser and go to `localhost:4000` is default address from jekyll, press <kbd>CTRL</kbd> + <kbd>C</kbd> to stop the jekyll server.

#### Adding remote repository

Before we adding remote repository, you must have [github](https://github.com/new) repository, if already have repository, just add github remote address to your local folder, with the following commands

```bash
$ git init # initializing project folder
$ git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git # change UPPERCASE with your own!
$ git add -A && git commit -m "Initialize" && git push -u origin master # push code to github
```

Now check your github repository, make sure the files is uploaded correctly.

#### Deploying to netlify

Go [vercel](https://vercel.app) dashboard, and following this step.

1. Create an account. (I recommend use git integration)
2. click `Add New...`, then choose `Project`.
2. then choose your repository where is the jekyll sources uploaded.
3. vercel smart enough to configuring, we just need's are hosting to click `Impot`, then `deploy`.

Wait for moment, and voila..! your site's are hosting and using `.vercel.app` tld, if your website wants to look professional, just buy a domain from your favorite domain store. or if you the first time, I advice using namecheap.com*(isn't sponsor)* \*based on my experienced it provides good service and have various TLDs.

So, what you waiting for, just create your own website for free.
