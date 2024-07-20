---
title: "News"
layout: textlay
excerpt: "News: CHRI Lab at Unimelb."
sitemap: false
permalink: /allnews.html
---

# News

<div class="well">
  {% for article in site.data.news %}
    <div class="row">
        <div class="col-sm-6">
          <p>{{ article.date }}<br/>
          {{ article.headline }}</p>
        </div>
    </div>
  {% endfor %}
</div>
<!--
<div class="well">
{% for article in site.data.news %}
{%- if article.img %}
<div class="row">
<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/news/{{ article.img }}" class="img-responsive" width="22%" style="float: left" />
{{ article.date }}<br/>
{{ article.headline}}</div>
</div>
{%- else -%}
<p>{{ article.date }}<br/>
{{ article.headline}}</p>
{%- endif %}
{% endfor %}
</div>
-->
