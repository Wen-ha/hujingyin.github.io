---
 layout: archive
 title:  "信息可视化作品集"
 categories: infovis
---
<div class='tableauPlaceholder' id='viz1515319455284' style='position: relative'><noscript><a href='#'><img alt='研究全国各省滑雪场、溜冰场、高尔夫球场、足球场的分布情况与数量比较等。 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CB&#47;CB2368BRF&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;CB2368BRF' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CB&#47;CB2368BRF&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1515319455284');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='827px';vizElement.style.height='796px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>


<div class="tiles">
{% for post in site.categories.infovis %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来---->