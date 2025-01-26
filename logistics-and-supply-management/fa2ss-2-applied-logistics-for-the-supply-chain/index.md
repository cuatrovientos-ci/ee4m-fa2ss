---
title: "FA2SS-2-Applied Logistics for supply chain"
slug: "fa2ss-2-applied-logistics-for-the-supply-chain"
permalink: "fa2ss-2-applied-logistics-for-the-supply-chain.html"
layout: page
---

{{ page.title }}

## Preview

You can have a look here
[preview](logistics-and-supply-management/fa2ss-2-applied-logistics-for-the-supply-chain/preview/index.html)

## SCORM

You can download the SCORM package to be integrated into an LMS, e.g. Moodle.

{% assign files = site.static_files  %}
{% for file in files   %}
{% if file.path contains page.slug and file.path contains  'zip' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}


{% assign files = site.static_files  %}

if files.length > 0

## Content

The theoretical contents of the course are shown below.

{% for file in files   %}
{% if file.path contains page.slug and file.path contains  'pdf' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}
  
end


