---
layout: index
title: Crédito Consolidado
overview: true
---

## Crédito Consolidado

<span class="latest-article">Últimos artigos</span>

<ul class="index">
  {% for post in site.categories.consolidado %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<hr/>

<div class="sponsor">
    {% include adsense.html %}
</div>
