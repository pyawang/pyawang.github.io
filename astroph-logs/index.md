---
layout: default
title: Home
---

# 🚀 My arXiv:astro-ph Literature Logs

Welcome to my daily paper reading journey. Here I document my insights and summaries of recent astrophysics and cosmology publications.

---

## 📄 Recent Logs

<ul>
  {% for post in site.posts %}
    <li>
      <strong>{{ post.date | date: "%Y-%m-%d" }}</strong> — 
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>