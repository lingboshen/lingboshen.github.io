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
  {% bibliography -f wp_papers -q @*[year={{y}}]* %}
  {% include figure.html path="assets/img/7.jpg" class="img-fluid rounded z-depth-1" %}
{% endfor %}

</div>

