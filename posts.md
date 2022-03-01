---
layout: default
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}; {{ post.author }}; {{ page.date | date: "%B %e, %Y" }}</a>
    </li>
  {% endfor %}
</ul>
