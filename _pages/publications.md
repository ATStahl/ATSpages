---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find a full list of my articles on <u><a href="https://scholar.google.com/citations?hl=en&user=8qB-798AAAAJ&view_op=list_works&sortby=pubdate&inst=3189495329521712930">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in /_publications reversed %}
  {% include archive-single.html %}
{% endfor %}
