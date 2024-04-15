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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Zhao-Hui Lu, Zhao Zhao, Xuan-Yi Zhang*, Chun-Qing Li, Xiao-Wen Ji, Yan-Gang Zhao. Simulating stationary non-Gaussian process based on unified Hermite polynomial model. Journal of Engineering Mechanics. 2020, 146(7): 04020067.
