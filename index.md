---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Fork, Clone & Enjoy.
description: Minimalistic Jekyll theme for your blog with plenty of features. Easy to install and setup.
---

{% for page in paginator.posts %}
{% include articles.html %}
{% endfor %}