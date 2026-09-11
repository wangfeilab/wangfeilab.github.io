---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  The selected publications below are complemented by the complete, current list on <u><a href="{{ site.author.googlescholar }}">Google Scholar</a></u> and <u><a href="{{ site.author.orcid }}">ORCID</a></u>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
