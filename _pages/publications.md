---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

More publications can be found on [Google Scholar](https://scholar.google.com/citations?user=Unl9W2IAAAAJ&hl=en).
<!--More publications can be found on <u><a href="{{https://scholar.google.com/citations?user=Unl9W2IAAAAJ&hl=en}}">Google Scholar</a>.</u>-->
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
