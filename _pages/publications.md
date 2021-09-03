---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

A list of my publications can also be found at <u><a href="https://scholar.google.com/citations?user=lO2wRlYAAAAJ&hl=en">my Google Scholar profile</a>.</u>

<!--- 
{% if author.googlescholar %}
  A list of works can also be found at <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
-->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
