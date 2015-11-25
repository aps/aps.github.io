---
layout: default	
title: Arne Poths - Blog
permalink: /blog/index.html
tab: Blog
---

# Blog Einträge

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} - {{ post.date | date: "%d. %B %Y" }} </a>
    </li>
  {% endfor %}
</ul>