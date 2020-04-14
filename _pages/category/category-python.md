---
title: "Post about Python"
layout: category
permalink: /categories/python
author_profile: false
---

{% assign posts = site.categories.python | sort:"date" %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
