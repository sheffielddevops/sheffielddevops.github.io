---
layout: default
---

<p>Here are our past events</p>

<div class="posts">
  {% for post in site.posts %}
      <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
  {% endfor %}
</div>
