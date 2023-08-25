---
layout: archive
title: "Patents"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.patents reversed %}
  {% include archive-single.html %}
{% endfor %}
