# External

v-002

---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.path }}</a>
    </li>
  {% endfor %}
</ul>

---
{{ site.pages }}
