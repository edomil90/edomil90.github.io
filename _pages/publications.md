---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

See my [Google Scholar](https://scholar.google.com/citations?user=LCRSDzEAAAAJ&hl=en) profile for the updated list.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}