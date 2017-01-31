---
layout: post
title: "Contents"
comments: true
categories: lecture
---

<a name="top"></a>

Landmark articles on personality

Core ideas in personality that you need to memorise.

Core building blocks in statistics that you need to memorize.

<ul>
  {% for post in site.categories.intro %}
	{% if post.url %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
	{% endif %}
  {% endfor %}
</ul>
