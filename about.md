---
layout: default
title: About
nav_order: 1
permalink: /about/
---
# About

<img src="{{ '/assets/images/ted-harbor-sunset.jpg' | relative_url }}" alt="Ted smiling at a harbor at sunset" style="float: right; width: 220px; max-width: 40%; margin: 0 0 1rem 1.5rem; border-radius: 8px;">

I'm a technical documentation leader with more than 20 years of experience driving measurable impact at Google and Meta. I build scalable content systems and lead high-performing teams that improve developer productivity and customer success.

[LinkedIn](https://www.linkedin.com/in/ted-prodromou/) · [GitHub](https://github.com/tedprodromou)

<div style="clear: both; display: flex; flex-wrap: wrap; gap: 0.75rem; margin-top: 2rem;">
{% assign photos = "ted-balloons.jpg|Ted in front of colorful hot air balloons;ted-balloon-flight.jpg|Ted smiling under a hot air balloon burner in flight;ted-eclipse.jpg|Ted in eclipse glasses with windblown hair;ted-plaid-closeup.jpg|Close-up of Ted in a plaid shirt and glasses;ted-jellyfish.jpg|Ted in silhouette in front of a jellyfish tank" | split: ";" %}
{% for p in photos %}{% assign parts = p | split: "|" %}
  <img src="{{ '/assets/images/' | append: parts[0] | relative_url }}" alt="{{ parts[1] }}" style="width: 150px; height: 150px; object-fit: cover; border-radius: 8px;">
{% endfor %}
</div>
