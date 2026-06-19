---
layout: page
permalink: /publications/
title: Publications
description: My publications in chronological order.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">Preprints</h2>
{% bibliography -f preprints --template bib %}

{% bibliography %}

</div>
