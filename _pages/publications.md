---
layout: archive
title: "Publications"
subtitle: "My research publications, with links to their full texts. More details can be found by clicking on each publication."
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
You can also find my articles on [my Google Scholar profile]({{ site.author.googlescholar }}).
{% endif %}

<div class="ag-list">
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
</div>
