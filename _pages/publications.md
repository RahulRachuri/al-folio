---
layout: page
permalink: /publications/
title: Publications
description:
years: [2020, 2018]
nav: true
---
More details are available at my [DBLP](https://dblp.uni-trier.de/pers/hd/r/Rachuri:Rahul) and [Google Scholar](https://scholar.google.com/citations?user=0mNNRIcAAAAJ&hl=da&oi=ao).
<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
