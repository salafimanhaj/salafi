---
title: Mawlid (the Prophet’s birthday)
---

<div id="archives" style="margin-top: 30px;">
<h3>Mawlid (Prophet’s birthday)</h3>
<ol>
  {% for post in site.categories.mawlid %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ol>
</div>
