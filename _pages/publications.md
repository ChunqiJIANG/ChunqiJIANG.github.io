---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

  You can also find my articles on <u><a href="https://scholar.google.de/citations?user=TJ8ipQQAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
