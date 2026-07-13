---
layout: about
title: about
permalink: /
subtitle: Research Scientist, Meta Reality Labs

profile:
  align: right
  image: cheng_zhang_profile.jpg
  image_circular: false

selected_papers: true
social: true

announcements:
  enabled: false
  scrollable: true
  limit: 8

latest_posts:
  enabled: false
---

I am a Research Scientist at [Meta Reality Labs](https://about.facebook.com/realitylabs/), with broad research interests in inverse and differentiable rendering, 3D reconstruction with foundation models and agents, multimodal learning, and robot learning.

I received my Ph.D. in Computer Science from the University of California, Irvine in 2022, where I was advised by Prof. [Shuang Zhao](https://shuangz.com/). My doctoral research focused on physics-based rendering and inverse rendering, particularly the recovery of geometry and material properties from physical measurements. To develop general and principled solutions to these inverse problems, I worked extensively on physics-based differentiable rendering. Prior to my Ph.D., I earned a B.E. in Electrical Engineering from Beijing University of Technology and an M.S. in Computer Science from Columbia University.

I was a recipient of the [2021 Facebook Fellowship](https://research.fb.com/fellows/zhang-cheng/) and the [2023 ACM SIGGRAPH Outstanding Doctoral Dissertation Award](https://www.siggraph.org/awards/outstanding-doctoral-dissertation-award/). Here is my [CV](/assets/pdf/cv.pdf) and [dissertation](/assets/pdf/thesis.pdf).

## News

{% assign news_items = site.data.news | sort: "date" | reverse %}

<ul class="news list-unstyled">
{% for item in news_items %}
  <li>
    <span class="news-date">{{ item.date | date: "%m/%Y" }}</span>
    {{ item.text | markdownify | remove: '<p>' | remove: '</p>' }}
  </li>
{% endfor %}
</ul>
