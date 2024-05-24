---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publichttps://github.com/academicpages/academicpages.github.io/blob/master/_pages/publications.mdations reversed %}
  {% include archive-single.html %}
{% endfor %}
