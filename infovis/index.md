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

![故事1.png](https://s1.ax1x.com/2018/01/07/pZ5wd0.png)
![故事2.png](https://s1.ax1x.com/2018/01/07/pZ5dZq.png)






<div class="tiles">
{% for post in site.categories.tableau %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis列出來-->
