---
layout: about
published: true
---

<div class="works">
  <h1>Finding Chopin, 2005-2015</h1>
  <ul>
    {% for post in site.categories.finding-chopin %}
    {% if post.url %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>
</div>
