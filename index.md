---
layout: page
title: Genome curation on emerging model species
---
## Building non-model species genome curation communities

The objectives of the project are to bring together software engineers and biologists to design
and implement essential software for answering questions in evolutionary genomics, and to
offer researchers the training material to be able to efficiently conduct these studies using both
existent and newly developed tools. We proposed to work toward two final products: 

  1. building novel or enhancing existing software that culminates in a single platform for genome analysis
  2. constructing a genomics curation curriculum for researchers of any career stage.



## Genome Train

<ul>
{% assign pages_list = site.pages %}
 {% for node in pages_list %}
    {% if node.title != null %}
      {% if group == null or group == node.group %}
        {% if page.url == node.url %}
        <li class="active"><a href="{{ BASE_PATH }}{{node.url}}" class="active">{{node.title}}</a></li>
        {% else %}
        <li><a href="{{ BASE_PATH }}{{node.url}}">{{node.title}}: {{node.url}}</a></li>
        {% endif %}
      {% endif %}
    {% endif %}
  {% endfor %}

</ul>

 