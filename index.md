---
layout: page
title: Steven Bird
tagline: Linguist, Computer Scientist, Preserver of Old Languages, ...
---
{% include JB/setup %}

{% for post in site.posts limit:5 %}
  <div class="post">
  {{ post.content }}
  <p class="signoff">
    &mdash;<a href="{{ post.url }}">{{ post.date | date: "%b %d, %Y" }}</a>
  </p>
  </div>
{% endfor %}


