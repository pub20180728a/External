# External

---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.path }}</a>
    </li>
  {% endfor %}
</ul>
