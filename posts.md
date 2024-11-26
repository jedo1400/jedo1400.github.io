---
layout: page
permalink: /posts
permalink_name: /posts
title: Posts
---

<!-- Lorem [ipsum dolor](read-me) sit amet, consectetur *adipiscing* **elit**, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat:

- List Item One -->

# 학습동아리
<ul>
    {% for post in site.posts %}
        {% if post.path contains "dlc" %}
            <li>
            <a href="{{ post.url }}">{{ post.title }}</a> <div style="display:inline; color:#7b7b7b">{{ post.date }}</div>
            </li>
        {% endif %}
    {% endfor %}
</ul>

---

# 알고리즘
<ul>
    {% for post in site.posts %}
        {% if post.path contains "alg" %}
            <li>
            <a href="{{ post.url }}">{{ post.title }}</a> <div style="display:inline; color:#7b7b7b">{{ post.date }}</div>
            </li>
        {% endif %}
    {% endfor %}
</ul>

---

# 리버싱
<ul>
    {% for post in site.posts %}
        {% if post.path contains "rev" %}
            <li>
            <a href="{{ post.url }}">{{ post.title }}</a> <div style="display:inline; color:#7b7b7b">{{ post.date }}</div>
            </li>
        {% endif %}
    {% endfor %}
</ul>
