---
layout: about
published: true
---

<div class="works">
  <h1>Ulterior Vistas, 2012-2014</h1>
  <ul>
    {% for post in site.categories.ulterior-vistas %}
    {% if post.url %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>
</div>
