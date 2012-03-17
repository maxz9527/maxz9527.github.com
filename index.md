---
layout: page
title: maxz9527 blog
---

   这是maxz9527的个人博客，关于生活，关于理想

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


