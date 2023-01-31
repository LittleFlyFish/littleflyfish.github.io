---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
The recent years publications are selected as the following:

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
