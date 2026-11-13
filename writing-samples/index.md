---
layout: default
title: Selected academic writing
---

# Selected academic writing  

Browse the available interactive pages below.

{% assign pages = site.data.html_pages | sort: "title" %}

<div class="html-page-list">
{% for page in pages %}

<a href="{{ site.url }}/{{ site.html }}/{{ page.file }}" target="_blank" rel="noopener noreferrer">{{ page.title }}</a>  

{{ page.description }}  

{% endfor %}  
</div>
