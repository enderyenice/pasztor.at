---
title: Blog
layout: wall
description: Read the IT blog of Janos Pasztor
---

<div class="wall">
<div class="wall__postlist">
{% for post in site.categories.blog offset:0 limit:8 %}
{% include wall-post.html %}
{% endfor %}
{% for post in site.categories.blog offset:8 %}
{% include wall-post-noimage.html %}
{% endfor %}
</div>
</div>
