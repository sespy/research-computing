---
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

{% for page in site.posts %}
{% include articles.html %}
{% endfor %}