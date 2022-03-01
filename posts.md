---
layout: default
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} by {{ post.author }} on {{ post.date| date: "%m-%d-%Y" }}</a>
    </li>
  {% endfor %}
</ul>
