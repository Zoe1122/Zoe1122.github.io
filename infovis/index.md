---
layout: archive
title: ""
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "信息可视化作品集展示"
tags: []
image: 
  feature:
  teaser:
---

信息可视化期末作品

![期末信息可视化作品.png](https://s1.ax1x.com/2018/01/06/pVUTLn.png)








<div class="tiles">
{% for post in site.categories.tableau %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis列出來-->
