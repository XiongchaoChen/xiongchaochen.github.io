---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can find my full publicaiton list on my [Google Scholar page](https://scholar.google.com/citations?user=k71vsAIAAAAJ&hl=en).


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


