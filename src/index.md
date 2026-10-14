---
title: My first page
layout: base.liquid
---

# A bold first step
Hello world!

## Blog Posts

<ul>
    {% for post in collections.posts %}
        <li><a href = "{{ post.url}}">{{ post.data.title }}</a></li>
    {% endfor %}
</ul>