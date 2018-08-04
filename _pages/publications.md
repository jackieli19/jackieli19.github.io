---
layout: archive
title: "Publications"
<<<<<<< HEAD
permalink: /publications/
=======
permalink: /research/
>>>>>>> parent of d0accde... Change
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
