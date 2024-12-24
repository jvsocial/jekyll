---
layout: default
---

# AWS DevOps Demos

This site contains a collection of demos organized by lessons.

## Lessons

<ul>
  {% for lesson in site.demos %}
    <li>
      <a href="{{ lesson.url }}">{{ lesson.data.title }}</a>: {{ lesson.data.description }}
    </li>
  {% else %}
    <li>No lessons available.</li>
  {% endfor %}
</ul>

Each lesson contains multiple demos that you can try.
