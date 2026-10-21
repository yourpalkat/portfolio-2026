---
layout: ../../layouts/ProjectLayout.astro
title: "Video Store Day"
slug: "vsd"
pubDate: 2026-10-20
featureOrder: 1
externalUrl: "https://videostoreday.com"
author: "Kat"
description: "Short description for meta tags and sharing purposes goes here."
introText: "I built a site to promote the annual international Video Store Day and allow stores all over the world to sign up and participate, on a shoestring budget and a very short timeline."
thumbnail:
  url: "vsd-thumb.jpg"
  alt: "Screenshot of the videostoreday.com website"
tags: ["projects", "ecommerce", "wordpress", "php"]
---

So. You remember video stores, right? You actually leave the house and go to a brick-and-mortar location, pick something out to watch and bring it home? Well, they're back, baby. Actually, they never left. But they are having something of a resurgence of late, as more people come to see the limitations of streaming services and want to regain the community aspect of going to a place where other film buffs hang out so they can discover new titles. Daniel Hanna, the proprietor of Toronto's Eyesore Cinema, was inspired by Record Store Day to start an annual celebration of video stores in 2010 as a way to promote these mostly local, independent businesses. Sixteen years later, Video Store Day was still going strong, and for the first time, had industry sponsors, allowing stores to offer exclusive video releases to help drum up business and excitement.

The previous Video Store Day site had been hacked and lost to time, and Daniel was making do with a quick-and-dirty no-code site that he'd thrown together himself, but that wasn't going to cut it with the renewed attention VSD was going to get. They needed a new presence on the internet to promote the celebration and announce exclusive VSD releases, but also to allow visitors to find a participating store near them, and also to allow potential participants to register their store for a nominal (sliding scale) fee, and for those registrations to automatically appear on the site, oh and maybe also they could sell some merchandise like t-shirts or stickers, oh and also it needs to be up in a month, oh and also there isn't really a budget. Phew!

The tight timelines made for a short discovery phase, which was unfortunate, not just because I like to spend a good amount of time with research and planning before settling on a technology stack and building, but because it led to difficulties down the line. I settled on Wordpress; my reasoning was that the client was familiar with it from previous sites, and it fit the budget requirements, plus I could use it as a headless CMS and build a custom front-end in React but still have access to its e-commerce capabilities via WooCommerce, since I would not have time to build out a full custom e-commerce solution in just a few weeks. Once the rubber hit the road, however, it became clear that a headless approach was not going to work in the time allotted. One unforseen problem after another slowed the pace of work, and after a few days of beating my head against the wall, I realized I was going to have to find another way. This led to a very late night where I wound up rebuilding the front end as an extremely customized Wordpress theme. This was a new challenge, since I'd never actually built a Wordpress theme before and my PHP was pretty rusty, but we got there in the end.

Another side-effect of the compressed timeline is that the design is deliberately fairly simple, but it's striking and effective. Angled blocks of bright colour delineate sections of content and oversize, bold typography for headlines steps in for the lack of imagery. The front page emphasizes the countdown to the big day and, once they were announced, the titles of the exclusive physical media releases. The page of participating stores is a simple responsive grid of cards with a simple location filter. It's eye-catching, performant, and responsive across all viewport sizes, and both the client and the industry partners were very happy with the result. I'm already looking forward to adding new features, even though next years' event is, at the time of this writing, fifty-one weeks away.
