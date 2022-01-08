---
layout: page
permalink: /publications/
title: research
#description: Please find my research here.
years: [2022] #include unique years with papers
nav: true
---
<!-- _pages/publications.md -->
#### Working papers
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f wp_papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

