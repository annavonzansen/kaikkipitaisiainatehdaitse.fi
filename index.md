---
title: kaikkipitaisijne...
author: Ville Korhonen
layout: default
---

<ul class="posts">  
    {% for post in site.posts limit:20 %}  
    <li>  
        <span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.github.url }}{{ post.url }}">  {{ post.title }}</a>
    </li>  
    {% endfor %}  
</ul>
