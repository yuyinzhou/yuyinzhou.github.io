---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
You can also find my full publication list on my [Google Scholar profile](https://scholar.google.com/citations?user=eiqVLC0AAAAJ&hl=en).


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
