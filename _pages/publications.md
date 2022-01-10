---
layout: page
permalink: /publications/
title: Research
#description: Please find my research here.
years: [2022] #include unique years with papers
nav: true
lang: en
---
<!-- _pages/publications.md -->
#### Working papers
<div class="publications">

{%- for y in page.years %}
  {% bibliography -f wp_papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

