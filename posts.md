---
layout: default
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} by {{ post.author }} on {{ page.date| date: "%m-%d-%Y" }}</a>
    </li>
  {% endfor %}
</ul>
