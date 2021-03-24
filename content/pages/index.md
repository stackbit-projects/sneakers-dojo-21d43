---
layout: home
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image_opacity: 65
    content: |
      # Kicking out the best Kicks!

      Don't see what you like here on our site, contact Kyle directly!
    actions:
      - title: See all items
        url: /store
        arrow: true
        style: primary
    background_image: images/circuit-board.png
  - type: featured_products_section
    section_id: best_sellers_section
    title: Best sellers
    icon: true
    light_title: true
    featured_products:
      - content/pages/products/plant1.md
      - content/pages/products/plant3.md
      - content/pages/products/plant5.md
      - content/pages/products/plant7.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - content/pages/category/bigplants.md
      - content/pages/category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    title: Testimonials
    testimonials:
      - author:
          name: 'Alex Patterson, MI, USA'
          location: 'Colorado, USA'
        text: Kyle's Shoe selection is mind blowing. He is really easy to work with!
      - author:
          name: Major Payne
          location: 'VA, USA'
        text: Are you serious he has stuff that hasn't even shipped yet!
  - type: promotion_section
    section_id: promotion_section
    title: New Shoes
    subtitle: from $149.99
    image: images/139769285_447001542989656_4527640685553868451_n.jpg
    background_image: images/139217622_318921876122822_540004059756308975_n.jpg
    cta:
      title: Discover
      url: /store
      style: secondary
      arrow: true
seo:
  title: Planty Theme
  description: The preview of the Planty theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Planty Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Planty theme
      keyName: property
    - name: 'og:image'
      value: images/header.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Planty Theme
    - name: 'twitter:description'
      value: The preview of the Planty theme
    - name: 'twitter:image'
      value: images/header.jpg
      relativeUrl: true
---
