---
layout: page
permalink: /publications/
title: publications
description: publications in reversed chronological order.
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012, 2010]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @article[year={{y}}]* %}
  {% bibliography -f papers -q @techreport[year={{y}}]* %}
{% endfor %}


</div>
