---
layout: page
permalink: /publications/
title: publications
description: publications in reverse chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<style>
  .publications h2.bibliography {
    color: var(--global-theme-color);
    font-weight: 500;
  }
</style>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
