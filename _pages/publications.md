---
layout: page
permalink: /publications/
title: publications
description: Our publications
years: [2022,2021,2020,2019,2018,2017,2016,2015,2014,2013]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f Tweezer -q @*[year={{y}}]* %}
  {% bibliography -f Microscope -q @*[year={{y}}]* %}
  {% bibliography -f CsYb -q @*[year={{y}}]* %}
  {% bibliography -f RbCs -q @*[year={{y}}]* %}

{% endfor %}

</div>
