---
layout: page
permalink: /publications/
title: publications
years: [2024, 2023, 2022, 2021]
nav: true
---

<!-- _pages/publications.md -->
<div class="publications">

{% for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
