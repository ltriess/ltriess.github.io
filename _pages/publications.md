---
layout: page
permalink: /publications/
title: publications
description:
years: [2022, 2021, 2020, 2019]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

All publications can also be found on <a href="https://scholar.google.com/citations?user=cBH8pFUAAAAJ&hl=de">Google Scholar</a>

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
