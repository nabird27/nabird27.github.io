---
layout: default
title: essays
---

> A collection of essays written for college coursework.  

{% comment %}
{% assign pages = site.data.html_pages | sort: "title" %}
{% endcomment %}

{% assign pages = site.data.html_pages %}
<div class="html-page-list">
{% for page in pages %}

<a href="{{ site.url }}/{{ site.html }}/{{ page.file }}" target="_blank" rel="noopener noreferrer">{{ page.title }}</a>  
<br>
{{ page.description }}  
<br><br>
{% endfor %}  
</div>
