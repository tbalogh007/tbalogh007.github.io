---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<h2>Publications</h2>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2>Working Papers</h2>
{% for post in site.working_papers reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2>Revise and Resubmit</h2>
{% for post in site.revise_resubmit reversed %}
  {% include archive-single.html %}
{% endfor %}
