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

<p>I have loved making art for as long as I can remember. I work mostly in watercolours, acrylics and ink, and I'm drawn to nature, everyday scenes, and the places I've lived in and travelled to. Here are some of my recent pieces.</p>

<div class="gallery">
{% for file in site.static_files %}
  {% if file.path contains '/images/art/' %}
    <a href="{{ file.path }}" target="_blank"><img src="{{ file.path }}" alt="{{ file.basename }}" loading="lazy"></a>
  {% endif %}
{% endfor %}
</div>
