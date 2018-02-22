---
layout: hary
---
<p>welcome to <a href="//nando.id">https://nando.id</a></p>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
