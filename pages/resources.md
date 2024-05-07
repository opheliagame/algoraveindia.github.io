---
layout: page
title: Learning Resources
author: Abhinay Khoparzi
---

[A big list of livecoding tools](https://github.com/lvm/awesome-livecoding)

[Official Guide to Hydra](https://hydra.ojack.xyz/docs/)

{% for post in site.categories.resources %}
  <a href="{{ site.github.url }}{{ post.url }}">
    <!-- <div class="featured-posts" {% if post.image %}style="background-image:url({{ site.github.url }}/assets/img/{{ post.image }})"{% endif %}> -->
      <!-- <h2><span> -->
        {{ post.title }}
      <!-- </span></h2> -->
    <!-- </div> -->
  </a>
{% endfor %}
