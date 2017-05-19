---
layout: page
title: Talks 
---

{% for talk in site.data.talks %}
<div class="talk">
<h3 class="title"><a href="{{talk.link}}">{{ talk.title }}</a></h3>
<p class="date">{{ talk.date }}</p>
<p class="org">{{ talk.org }}</p>
<p class="location">{{ talk.location }}</p>
</div>
{% endfor %}



