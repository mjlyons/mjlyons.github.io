---
layout: default
---
# Mike Lyons

👋 Hi I'm Mike!

- [GitHub](https://github.com/mjlyons)

## Posts

<ul class="post-list">
{% for post in site.posts %}
  <li><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%b %-d, %Y" }}</time> <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
