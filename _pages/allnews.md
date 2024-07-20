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
      {%- if article.img %}
        <div class="col-sm-6 clearfix">
          <img src="{{ site.url }}{{ site.baseurl }}/images/news/{{ article.img }}" class="img-responsive" width="22%" style="float: left; margin-right: 10px;" />
          <p>{{ article.date }}<br/>
          {{ article.headline }}</p>
        </div>
      {%- else -%}
        <div class="col-sm-6">
          <p>{{ article.date }}<br/>
          {{ article.headline }}</p>
        </div>
      {%- endif %}
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
