---
layout: default
title: Home
---

# Welcome to My Blog

This is a simple blog built with GitHub Pages and Jekyll.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
