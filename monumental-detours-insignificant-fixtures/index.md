---
layout: about
published: true
---

<div class="works">
  <h1>Monumental Detours / Insignificant Fixtures, 2008-2011</h1>
  <ul>
    {% for post in site.categories.monumental-detours-insignificant-fixtures %}
    {% if post.url %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>
</div>
