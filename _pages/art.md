---
layout: archive
title: "Art"
permalink: /art/
author_profile: true
---

<style>
  .gallery { column-count: 3; column-gap: 12px; }
  .gallery img {
    width: 100%; margin-bottom: 12px; border-radius: 8px;
    break-inside: avoid; display: block; transition: opacity .2s;
  }
  .gallery img:hover { opacity: .85; }
  @media (max-width: 800px) { .gallery { column-count: 2; } }
  @media (max-width: 500px) { .gallery { column-count: 1; } }
</style>

<div class="gallery">
{% for file in site.static_files %}
  {% if file.path contains '/images/art/' %}
    <a href="{{ file.path }}" target="_blank"><img src="{{ file.path }}" alt="{{ file.basename }}" loading="lazy"></a>
  {% endif %}
{% endfor %}
</div>
