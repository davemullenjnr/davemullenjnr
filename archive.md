---
layout: archive
title: Archive
excerpt: Archive of one-off photographs, graphic designs, logo designs, etc.
permalink: /archive/
category: work
images:
  - src: Beach-Fossils-Brooklyn-band-t-shirt-in-white.jpg
    alt: Beach Fossils band t-shirt in white
  - src: fox-diving-head-first-into-snow-north-america.jpg
    alt: An illustration of a North American fox hunting in the snow by diving head first to catch its prey
  - src: humans-of-dementia-logo.jpg
    alt: humans of dementia logo
    class: archive-border
  - src: let's-go-down-in-history-not-down-with-it-XR-Extinction-Rebellion-climate-design.jpg
    alt: let's go down in history, not down with it for Extinction Rebellion protest
  - src: let's-go-down-in-history-XR-Extinction-Rebellion-climate-design.jpg
    alt: let's go down in history, not down with history. Climate protest design for Extinction Rebellion.
  - src: Mac-Demarco-band-t-shirt-design.jpg
    alt: Mac DeMarco band t-shirt design
  - src: Mac-Demarco-print-design.jpg
    alt: Mac DeMarco print poster design
  - src: Scott-Westgarth-personal-trainer-logo-design.jpg
    alt: Scott Westgarth personal trainer logo design
    class: archive-border
  - src: Scott-Westgarth-personal-training-logo-design.jpg
    alt: Scott Westgarth personal trainer logo brand design
  - src: Sheffield-Park-Hill-flats-brutal-architecture-aeroplane-look-up.jpg
    alt: An aeroplane flying above Park Hill flats in Sheffield
  - src: Tame-Impala-Kevin-Parker-logo-design.jpg
    alt: Tame Impala graphic design featuring Kevin Parker
    class: archive-border
  - src: Tame-Impala-t-shirt-featuring-Kevin-Parker.jpg
    alt: Tame Impala t-shirt design with an illustrated head of Kevin Parker
  - src: the-barbican-centre-shakespeare-tower-brutalist-architecture-london.jpg
    alt: The Barbican Shakespeare Tower in London. Brutal architecture dystopian photograph
---

{% for image in page.images %}
  {% cloudinary /assets/img/posts/archive/{{ image.src }} class="{{ image.class }} mb-2 blog-image border-radius" alt="{{ image.alt }}" %}
{% endfor %}