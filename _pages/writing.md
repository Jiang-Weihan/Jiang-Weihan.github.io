---
layout: archive
title: "Blogs"
permalink: /blogs/
author_profile: true
redirect_from:
  - /writing/
---

Essays and Notes
------

This page will collect essays, reading notes, and short research reflections on games, culture, player experience, and interactive media.

Planned Topics
------

- Farming games and the imagination of rural life.
- Gender, narrative, and women-friendly games.
- Cultural metaphors in everyday game mechanics.
- Games, learning, and implicit education.

Blog Archive
------

{% include base_path %}

{% for post in site.posts reversed %}
  {% include archive-single.html %}
{% endfor %}
