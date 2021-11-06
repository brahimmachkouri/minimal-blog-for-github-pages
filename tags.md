---
title: Tags
---

{% for tag in site.tags %}
  {{ tag[0] }} <a href="#" onClick="lunr_search('{{ tag[0] }}');">({{ tag[1].size }})</a> <br>
{% endfor %}
