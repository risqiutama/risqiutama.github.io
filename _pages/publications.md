---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Please find the full list of my papers on [my Google Scholar profile](https://scholar.google.com/citations?user=7wZkVT8AAAAJ&hl=en)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=7wZkVT8AAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
