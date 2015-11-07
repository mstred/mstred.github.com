---
layout: page
title: Log
---

<section>
  <p>
    <ul class="unbulleted">
    {% for post in site.posts %}
      <li class="monotyped">
        <span>{{ post.date | date: '%Y-%m-%d' }}</span>
        <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
    </ul>
  </p>
</section>
