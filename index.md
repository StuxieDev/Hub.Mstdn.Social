---
title: Mstdn Hub
header: Mstdn Hub
description: Explore and discover social media the fun way.
permalink: /
layout: default
---

{% for post in site.posts %}
  <p class="blog-item"><b><a href="{{ post.url }}">{{ post.title }}</a></b><br>
  <span class="post-description">{{ post.description }}</span><br>
  <span class="post-meta">📅 {{ post.date | date_to_string }}</span></p>
{% endfor %}
