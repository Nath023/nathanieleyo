---
layout: default
---

# Nathaniel Eyo

Web developer, digital builder, and curious mind.

I write about technology, business, ideas, and lessons from the things I build.

## Essays

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

<small>{{ post.date | date: "%B %-d, %Y" }}</small>

{{ post.excerpt | strip_html | truncatewords: 35 }}

{% endfor %}
