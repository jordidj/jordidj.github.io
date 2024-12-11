---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## List of collaborators
* Claes, Niels
* De Vadder, Joeri
* Keppens, Rony
* Kuczyński, Michał D.
* Sen, Samrat

## List of publications
Click a title to see the abstract and any errata.

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
