---
title: Hello
layout: default
---

<ul>
  {% for post in site.posts %}
      <li style="list-style-type:none">
        <h2>{{ post.title }}</h2>
        <div id="list">
          {{ post }}
        </div>
        <br/>
      </li>
  {% endfor %}
</ul>