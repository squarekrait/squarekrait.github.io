---
layout: page
title: Posts
---

<ul>
  {% for post in site.posts %}
    <li style="">
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span style="color: #9a9a9a; float: right">
        {{ post.date | date: "%d %B %Y" }}
      </span>
    </li>
  {% endfor %}
</ul>
