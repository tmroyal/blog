---
layout: default
title: About
---

{{ site.description }}

### Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

### Social 

[Github](https://github.com/tmroyal){:target="_blank"}