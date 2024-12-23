---
layout: default
title: Categories
---

<!-- This can be a simple page that lists all categories -->
<h1>All Categories</h1>
<ul>
{% for category in site.categories %}
  <li>
    <a href="{{ site.baseurl }}/categories/{{ category[0] | downcase }}">
      {{ category[0] }}
    </a>
  </li>
{% endfor %}
</ul>
