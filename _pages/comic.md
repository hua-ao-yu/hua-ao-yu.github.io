---
layout: archive
title: "Comic"
permalink: /comic/
author_profile: true
---

{% include base_path %}

{% for post in site.comic reversed %}
  {% include archive-single.html %}
{% endfor %}
