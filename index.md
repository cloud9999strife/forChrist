---
layout: page
title: For Christ
tagline: For the Lord of Glory
description: Apologetics, theology, philosophy, to His honor.
---
# Posts
<ul class="posts">
{% for post in site.posts limit: 20 %}
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>
