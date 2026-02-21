---
layout: default
title: Scholarship Hub
---

# 🌍 Global Scholarship Hub

Daily updated scholarship opportunities worldwide.

---

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})

- Country: {{ post.country }}
- Level: {{ post.level }}
- Deadline: {{ post.deadline }}

---

{% endfor %}
