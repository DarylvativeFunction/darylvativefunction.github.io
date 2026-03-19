---
permalink: /blog/
title: "Blog"
author_profile: true
---

Welcome to my blog. I write about energy systems, engineering, research, and ideas I am exploring.

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
