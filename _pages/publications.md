---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true

---

{% include base_path %}

  You can also find his full articles at 
  
  - <a href="https://scholar.google.de/citations?user=TJ8ipQQAAAAJ&hl=en">Google Scholar</a>
  - [ResearchGate](https://www.researchgate.net/profile/Chunqi-Jiang-3)

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
