---
title: "Chri Lab - Yan"
layout: personal
permalink: /people/yan/
sitemap: false
excerpt: "Personal webpage of Yan"
---
{%- assign data = site.data.people -%}
{%- assign member = data.yan -%}

<div class="row">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="22%" style="float: left" />
  <h1>{{ member.name }}</h1>
  <i style="font-size:20px">{{ member.info }}</i><br>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-3x"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-3x"></i></a> {% endif %}
  {% if member.twitter %} <a href="{{ member.twitter }}" target="_blank"><i class="fa fa-twitter-square fa-3x"></i></a> {% endif %}
  <!-- {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %} -->
  <ul style="overflow: hidden">

  {% for education in member.education %}
	<li> {{ education }} </li>
  {% endfor %}

  </ul>
</div>

## Biography

<p>
I'm a first-year Ph.D. student from the School of Computing and Information Systems, University of Melbourne. I'm supervised by Dr.Wafa Johal, Dr.Jorge Goncalves, and Dr.Jarrod Knibbe from the Human-Computer Interaction Group and Human-Robot Interaction Lab. My research interest focuses on Human-Robot Collaboration. Before starting my Ph.D., I completed my Bachelor's degree in Systems Engineering at the City University of Hong Kong. After that, I worked as a Research Engineer for two years at the Institute for AI Industry Research at Tsinghua University.  
<br/>

Contact me: yanzhang15[at]student[dot]unimelb[dot]edu[dot]au
<br/>
[Google Scholar](https://scholar.google.com/citations?user=CyIEsPgAAAAJ&hl=zh-CN)
<br/>
[LinkedIn](https://www.linkedin.com/in/yan-zhang2332/)
<br/>
[Personal Webpage](https://yzhang2332.github.io/yanzhang/)

</p>
