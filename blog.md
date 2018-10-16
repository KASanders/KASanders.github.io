---
layout: page
title: Blog
---

{% for post in site.posts %}
  * <strong>{{ post.date | date_to_string }}</strong> &raquo; [ {{ post.title}} ]({{ post.url }})
{% endfor %}
