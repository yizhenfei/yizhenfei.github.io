---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

{% for post in site.posts %}	
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
> {{ post.date | date: "%B %e, %Y" }}
{{ post.excerpt }}
{% endfor %}
