---
title: Teaching Assistant
type: TA
# TA page
# v2.0
# https://github.com/cotes2020/jekyll-theme-chirpy
# © 2017-2019 Cotes Chung
# MIT License
---
<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
