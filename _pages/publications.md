---
layout: page
permalink: /publications/
title: publications
description: For an up-to-date list, please refer to my [Google Scholar](https://scholar.google.com/citations?user=9lh2gH8AAAAJ&hl=en) page.
years: [2021,2020,2019,2018,2017]
nav: true
---

(*=equal contribution)

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
