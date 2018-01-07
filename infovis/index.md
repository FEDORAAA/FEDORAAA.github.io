---
layout: archive
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: 
tags: []
title: "信息可视化作品集"<p>
image: 
  feature: 仪表板1.png
  teaser:
---


<div class="tiles">
{% for post in site.categories.visualization %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 visualization 的列出来-->
