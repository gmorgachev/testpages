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
          <embed width="100%" height="500"
src="https://www.youtube.com/embed/tgbNymZ7vqY">
        </div>
        <br/>
      </li>
  {% endfor %}
</ul>