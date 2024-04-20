---
title: "HRI @ Unimelb - Home"
layout: homelay
excerpt: "HRI at University of Melbourne."
sitemap: false
permalink: /
---

<h3> About </h3>

<div>

Welcome to the Human-Robot Interaction Research Group at the University of Melbourne. 

Our mission is to create autonomous robots that act smoothly and safely with humans. We focus on key areas such as behavioural analytics, co-learning environments for humans and robots, and the personalization and adaptation of autonomous robots to enhance their performance in human interactions.

We are at the leading edge of human-robot interaction research, addressing challenges such as safe drone navigation in crowded spaces, personalized learning solutions with assistive robots, and visualizing uncertainty in high-stake scenarios involving robots...

</div>

<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover" >
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
        <li data-target="#carousel" data-slide-to="4"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">
        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/1.png" alt="Slide 1" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/2.png" alt="Slide 2" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/3.png" alt="Slide 3" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/4.png" alt="Slide 4" />
        </div>
         <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/cellulo.png" alt="Slide 4" />
        </div>
         <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/carousel/chri-logo.png" alt="Slide 4" />
        </div>
       </div>
    </div>
  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>

<!--
<h3> Recent Papers </h3>

<div class="publications">
{% comment %}
{% bibliography -f papers --max 5 %}
{% endcomment %}
</div>
-->

<h3> Selected Recent Publications </h3>

<div class="publications">
{% bibliography -f papers -q @*[selected=yes]* --max 5 %}
</div>
