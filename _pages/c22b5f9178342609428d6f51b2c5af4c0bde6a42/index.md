---
layout: inclusive
title: "Personal"
permalink: "/pages/c22b5f9178342609428d6f51b2c5af4c0bde6a42/"
---

<section>
  <ul class="listing">
    {% for post in site.posts %}
      {% unless post.draft %}
      <li>
        <span>{{ post.date | date: "%A %-d %B %Y" }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
      {% endunless %}
    {% endfor %}
  </ul>
</section>
