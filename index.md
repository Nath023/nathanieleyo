---

## layout: default

# Nathaniel Eyo

I’m a web developer and digital builder interested in technology, business, and the process of turning ideas into useful things.

This is my personal space for essays, notes, experiments, and lessons learned along the way.

---

## Writing

{% for post in site.posts %}

### [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %-d, %Y" }}*

{{ post.excerpt | strip_html | truncatewords: 40 }}

{% endfor %}

---

[About](about.md) · [GitHub](https://github.com/Nath023)
