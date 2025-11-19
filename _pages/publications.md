---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find the most part of my publications on <a href="https://scholar.google.com/citations?user=zgqDWcwAAAAJ&hl=de">my Google Scholar profile</a> and in <a href="https://www.researchgate.net/profile/Abdullah-Shafqat?ev=hdr_xprf">ResearchGate</a>.


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
