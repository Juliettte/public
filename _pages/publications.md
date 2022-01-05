---
layout: page
permalink: /publications/
title: publications
description: publications and technical reporte in reversed chronological order. 
years: [2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012, 2011, 2010, 2009, 2008, 2007]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @article[year={{y}}]* %}
{% endfor %}


</div>
<div class="techreports">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @techreport[year={{y}}]* %}
{% endfor %}


</div>
