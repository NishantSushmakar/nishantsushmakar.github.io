---
layout: page
title: Blog
permalink: /blog/
---

# Blog

Here are my latest blog posts on Medium:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date_to_string }}</small>
    </li>
  {% endfor %}
</ul>
