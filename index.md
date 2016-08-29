---
# YAML Front Matter
layout: default
title: my first jekyll site
---
# Jekyll Prototyping Page

{% for post in site.posts %}
- [{{　post.title　}}]({{ site.baseurl }}{{ post.url }})
{% endfor %}

