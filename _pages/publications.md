---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find the full publication list on <u><a href="https://inspirehep.net/authors/2078475?ui-citation-summary=true">my INSPIREHEP profile</a>.</u>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
