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

<div class='tableauPlaceholder' id='viz1515253754939' style='position: relative'><noscript><a href='#'><img alt='故事 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;WD&#47;WDP5SK239&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;WDP5SK239' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;WD&#47;WDP5SK239&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1515253754939');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='800px';vizElement.style.height='827px';                    var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>








<div class="tiles">
{% for post in site.categories.tableau %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis列出來-->
