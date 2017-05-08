---
layout: hary
---
<p>Welcome!</p>
<p>Please enjoy..</p>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
