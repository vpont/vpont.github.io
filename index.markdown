---
layout: default
---

{% for post in site.posts %}

## [{{ post.title|upcase }}]({{ post.url }})

[{{ post.date | date: '%B %d, %Y' }}]

{{ post.excerpt }}

{% endfor %}
