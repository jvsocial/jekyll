# Welcome to My Demos Site

This site contains a collection of demos organized by lessons.

## Lessons

<ul>
  {% for lesson in site.demos %}
    <li>
      <a href="{{ lesson.url }}">{{ lesson.data.title }}</a>: {{ lesson.data.description }}
    </li>
  {% endfor %}
</ul>

Each lesson contains multiple demos that you can try.

---
