---
abstract: Wagtail is one of the most popular content management systems in the Django
  world, and the Wagtail team is committed to making it as easy as possible to create
  accessible websites. It still requires intention and effort on the part of a developer
  creating a Wagtail website, though. Learn the tools and techniques you need to set
  your editors up for success.
accepted: true
category: talks
date: 2023-10-18 13:20:00-04:00
end_date: 2023-10-18 14:05:00-04:00
group: talks
layout: session-details
permalink: /talks/best-practices-for-making-a-wagtail-site-as-accessible-as-possible/
presenter_slugs:
- scott-cranfill
published: true
room: Online talks
schedule_layout: full
sitemap: true
slug: best-practices-for-making-a-wagtail-site-as-accessible-as-possible
summary: ''
tags:
- accessibility
- wagtail/butter/other CMS
title: Best Practices for Making a Wagtail Site as Accessible as Possible
track: t2
---

Over the past few years, the Wagtail CMS core team and accessibility subteam have made [significant commitments to improving Wagtail's accessibility](https://wagtail.org/accessibility/) – both the CMS interface itself as well as the websites that it produces. This talk is focused on the latter, aiming to show how you (a developer of a Wagtail-powered site) can set up your models, templates, and workflows in order to make it as easy as possible for your editors to create websites that are as accessible _as possible_. I say "as possible" because it's important to recognize that it's virtually impossible for a website to ever be considered 100% accessible, but with some care put into what we do on the development side, we can prevent some of the most widespread accessibility issues that users may come across.

Some of the topics that are planned to be covered include:
- How to configure and use Wagtail's [new built-in accessibility checker](https://wagtail.org/blog/introducing-wagtails-new-accessibility-checker/)
- Ensuring alt text is used appropriately (Spoiler alert: every image doesn't need alt text!)
- Usage of `aria-label` attributes to provide essential context to screen readers
- Custom validation to ensure that a page has a logical heading order
