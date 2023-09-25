---
layout: archive
title: "My Chronicle"
permalink: /chronicle/
author_profile: true
---

{% include base_path %}

{% for post in site.chronicle reversed %}
  <h2>{{ post.title }}</h2>
{% endfor %}

