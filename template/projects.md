---
layout: inner
title: Projects
permalink: /projects/
---

<!-- ## Programming
- [FocusBoom](https://github.com/bensim0305/FocusBloom)
- [Live Sampler](https://brandinmuc.github.io/Sampler-for-Algorithmic-Music-Composition/)

## Media Art
- [Reimagined Album](https://newart.city/show/maadp2023-a)

## Photography
- [Summer Breeze 2024]()
- [Visuals Series at UChicago](http://instagram.com/visualsuchi/)
 -->

<h3>Projects</h3>
<!-- <h2>Programming</h2>
<h2>Media Art</h2> -->
<div class="project-grid">
  {% for project in site.projects %}
    <div class="project-card">
      <a href="{{ project.url }}">
        <img src="{{ project.featured_image }}" alt="{{ project.title }}">
        <h3>{{ project.title }}</h3>
        <p> {{ project.lead_text }}</p>
      </a>
    </div>
  {% endfor %}
</div>

