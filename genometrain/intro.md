The Genome Train seeks to educate and empower researchers with an understanding of the process of genome sequencing. We present the process of automated annotation and manual curation of a newly sequenced genome, both in ideal conditions and in the current state of affairs. 

We outline best practices, such as describing some of the tools, the methods, and the players working behind the scenes, converting data into testable hypotheses (and not—as it may be often assumed—facts). 

Throughout this process, we wish to lead biologists themselves to undertake an aspect of quality control that only they, as domain experts who understand the biology of the species, can perform. 

The analogy of a train journey allows shows best practice guidelines and checklists as station stops that force us to evaluate our position before investing further effort. As your research community undertakes its own long journey, we hope that this journey planner will help you reach your destination: a high quality community resource that ensures no evolutionary question is beyond the reach of a long-term research program.

The work here described is part of the published work (reference) that resulted from the working group on "Building non-model species genome curation communities", funded by NESCent.


<ol type="A">
{% assign pages_list = site.pages | sort:"url" %}
 {% for node in pages_list %}
    {% if node.tag == 'stationoverview' %} 
      {% if group == null or group == node.group %}
        <li><strong><a href="{{ BASE_PATH }}{{node.url}}">{{node.title}}</a></strong></li>
      {% endif %}
    {% endif %}
  {% endfor %}
</ol>
