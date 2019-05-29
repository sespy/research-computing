---
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
  {% include articles.html %}
  {% endfor %}
</ul>