---
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
---

{% for page in paginator.posts %}
{% include articles.html %}
{% endfor %}
