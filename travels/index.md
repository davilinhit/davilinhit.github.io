---
layout: page
title: Travels
permalink: /travels/
---

<div class="container">
  {% for post in site.categories.travels %}
  <div style="float:left; margin: 0 1%; width: 45%;">
    <img src="{{post.image}}" style="width: 100%; padding: 0px; margin: 0px;">
    <div style="height: 2.8em; overflow:hidden; text-align:center; margin-bottom: 10px;">
       <strong><a href="{{ post.url }}">{{ post.title }}</a></strong>
    </div>

  </div>


  {% endfor %}
</div>
