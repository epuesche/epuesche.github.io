---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Selected relevant publications are listed below.

"Search for Ultraheavy Dark Matter from Observations of Dwarf Spheroidal Galax-
ies with VERITAS", D. Tak and E. Pueschel with the VERITAS collaboration and
N. Rodd, The Astrophysical Journal, 945:101 (2023); arXiv:2302.08784.

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
