---
layout: page
title: Writing 
---

<ul class="list">
{% for post in site.posts %}
<li>
<h3><a href="{{ post.baseurl}}{{ post.url }}">{{ post.title }}</a></h3>
<small class="meta">{{ post.date | date_to_string }}</small>
</li>

{% endfor %}
</ul>

