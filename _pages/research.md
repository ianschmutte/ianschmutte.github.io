---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

You can also find my articles on my [Google Scholar profile](http://scholar.google.com/citations?user=mwB4cQoAAAAJ).

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single-research.html %}
{% endfor %}
