---
layout: default
---
<h1>welcome</h1>
<h2>please enjoy..</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
