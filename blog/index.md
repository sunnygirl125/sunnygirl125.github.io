---
layout: default
title: Blog
permalink: /blog/
---

[About Me](/) | [Portfolio](/portfolio/) | [Blog](/blog/)

# Blog

Welcome to my thoughts and notes.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
