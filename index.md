---
layout: page
title: Willkommen auf David's Seite
---
{% include JB/setup %}
 
    Autor :
      Name : David Quirmbach
      email : david.quirmbach@ilc-solutions.de
      GitHub : IlcDavid


## Meine Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



