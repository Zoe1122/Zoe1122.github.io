---
layout: archive
title: "信息可视化笔记"
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "好记性不如烂笔头"
tags: []
image: 
  feature: 
  teaser:
---

 在此展示网页设计和信息可视化的读书笔记

<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 posts列出來-->
