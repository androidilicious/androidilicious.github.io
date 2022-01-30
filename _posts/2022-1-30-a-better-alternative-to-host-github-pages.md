---
layout: post
title: How I found a better alternative to host my blog. It's completely free too!
published: true
author: diwaspuri
feature-img: "assets/img/feature-img/desk-messy.jpeg"
thumbnail: "assets/img/thumbnails/feature-img/desk-messy.jpeg"
tags: github pages blog website domain dns nameserver arvixe
---

I've been dabbling with blogging for quite some time now, and I must warn you that I'm not very good at it. I think I am more interested in the technological side of things since I enjoy experimenting with different platforms. This has allowed me to identify an ideal solution to host my blog. Throughout this process, I've come to learn that paying for hosting for a simple landing page or blog is a waste of money.

It's crucial to realize for the uninitiated that all websites have numerous layers of intricate things going on behind the scenes to deliver the contents to the screen. This includes the domain name, which in my case is www.diwaspuri.com, as well as the server that hosts the content that appears when www.diwaspuri.com is accessed. Not to mention the thousands of kilometers of fiber cables that travel beneath the oceans floor to the mobile phone towers that beam the internet to your phones. However, in this scenario, remember just two things: the domain name and the computer/server that has the files that are referenced when the domain is used.

When I first began practicing web programming, I was naturally drawn to the easiest option. I didn't realize you could buy the domain name and hosting separately back then. So, when I bought the name and hosting package, the company selling it was largely profiting from the hosting service. To attract more clients, the domain name would generally have a lower price tag connected to it at first. My first hosting provider was Arvixe, which I subsequently discovered was a part of the same parent business that also offers BlueHost, HostGator, JustHost, HostNine, HostMonster, and other hosting services.

When I first stumbled across [GitHub Pages](https://pages.github.com/), it occured to me that a free service like this would not only be a money saving but also a learning opportunity. GitHub pages however are only good for static websites and can't handle extensive backend operations, but they're great for a blogs like this.

### How to create a GitHub page?

In order to create a GitHub page, you first need an account with the service. Then just create a GitHub repository and name it as `<anyname>.github.io`. After that, add static files to the repository after which you will be good to go.

You can also use one of several [Jekyll](https://jekyllthemes.io/) themes if you don't want to waste time developing a website that looks nice. You'll just need to push one of the themes to the repository after making any necessary changes.

### Have a domain name?

If you have purchased a domain name and want to use it instead of the standard `<anyname>.github.io`, simply go to the dashboard of the service where you bought your domain and point it to the GitHub servers as described in [this](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site) page. You will also need to add a CNAME file in your GitHub repository for your name servers to be able to recognize it.

### Final Thoughts

If you're a casual blogger or enjoy tinkering with things on the internet, GitHub pages may be of interest to you because they're simple to set up and load quickly for end users. For this reason, I utilize this service to power my site, and you might want to do the same.