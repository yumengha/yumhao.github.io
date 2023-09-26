---
layout: post-list
title: "Hobbies & Habits"
permalink: /hobbies/
author_profile: true
---

{% include base_path %}

{% for post in site.hobbies reversed %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  {{ post.content }}
{% endfor %}
