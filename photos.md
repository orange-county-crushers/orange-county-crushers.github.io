---
layout: gallery
title: Photos
description: Crushers in action
image: assets/images/taran_kaden.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">
<p>Our Crushers in action</p>
{% for image in site.images %}
     <a href="{{ image.url }}">{{ images.name }}</a>
     {% if image.extname == 'jpg' %}
         <img src="{{ image.url }}" />
     {% endif %}
{% endfor %}

</div>

