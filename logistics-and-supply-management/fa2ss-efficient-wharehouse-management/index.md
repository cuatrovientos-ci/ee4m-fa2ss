---
title: "FA2SS-1-Efficient Wharehouse Management"
slug: "fa2ss-efficient-wharehouse-management"
permalink: "fa2ss-efficient-wharehouse-management.html"
layout: page
---

{{ page.title }}


Puedes dar un vistazo aquí [preview](logistics-and-supply-management/fa2ss-efficient-wharehouse-management/preview/index.html)

Puedes descargar el paquete SCORM para ser integrado en LMS, e.g. Moodle.

{% assign files = site.static_files  %}
{% for file in files   %}
{% if file.path contains page.slug and file.path contains  'zip' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}

{% assign files = site.static_files  %}

{% if files.length > 0 %}

The theoretical contents of the course are shown below.

{% for file in files   %}
{% if file.path contains page.slug and file.path contains  'pdf' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}
  
{% endif %}


