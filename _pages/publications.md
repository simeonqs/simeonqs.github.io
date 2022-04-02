---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<div class='altmetric-embed' data-badge-type='donut' data-doi="10.1038/nature.2012.9872"></div>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
