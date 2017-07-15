---
layout: page
title: Talks 
---

<dl class="lh-title mt0">
{% for talk in site.data.talks %}
  <div class="pv3">
  <a class="f3 link black dim b bg-light-yellow" href="{{ talk.link }}" target="_blank">{{ talk.title }}</a>
  <dd class="f4 ml0">{{ talk.org }}</dd>
  <dd class="f5 ml0">{{ talk.date }}</dd>
  <dd class="f5 ml0">{{ talk.location }}</dd>
  </div>
{% endfor %}
</dl>



