---
layout: page
permalink: /publications/
title: Research 
order: 2
description: 
years: [2021, 2019]
nav: true
---

<style>
.myDiv {
    margin: 30px 0px 30px 0px;
}
</style>


<div class="publications">

<!--
{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}} & abbr={{"Working Paper"}}]* %}
{% endfor %}
-->

<div class="myDiv">
<h2> Working Papers </h2>
{% bibliography -f papers -q @*[type=Working Paper]* %}
</div>

<div class="myDiv">
<h2> Book Chapters </h2>
{% bibliography -f papers -q @*[type=Book Chapter]* %}
</div>

</div>
