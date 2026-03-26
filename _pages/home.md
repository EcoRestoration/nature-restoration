---
layout: home
title: "Peatland restoration guidelines"
hero_image: "/assets/backgrounds/Veengebied_in_Finland_Yves_Adams_A4_74825.jpg"
image_credit: "Yves Adams, Vilda"
hero_subtitle: "Practical restoration pathways for Europe's mires, bogs and fens"
permalink: /
---

<section class="hero {% if page.hero_image %}has-image{% endif %}"
         style="{% if page.hero_image %}background-image: url('{{ page.hero_image | relative_url }}');{% endif %}">
  <div class="hero-inner">
    <span class="hero-eyebrow">Peatland restoration guidelines</span>
    <h1>{{ page.title }}</h1>
    {% if page.hero_subtitle %}
      <p class="hero-subtitle">{{ page.hero_subtitle }}</p>
    {% endif %}
  </div>
  {% if page.image_credit %}
    <div class="hero-attribution">Photo by: {{ page.image_credit }}</div>
  {% endif %}
</section>

{{ content }}
