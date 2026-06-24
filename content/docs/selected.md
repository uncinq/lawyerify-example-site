---
isPage: true
draft: false
title: Selected
description: Add selected items section (posts, projects, publications, casestudies…)
icon: check-check
hero:
  surtitle: Blocks
  title: Selected sections
  text: Add selected items section (posts, projects, publications, casestudies…).
  ctas:
    - text: Documentation
      url: https://www.hugolify.io/docs/blocks/selected/
      blank: true
    - text: Page code on Github
      url: https://raw.githubusercontent.com/Hugolify/hugolify-example-site/refs/heads/main/content/docs/selected.md
      blank: true
blocks:
  
  - type: selected-posts
    section: posts
    show_more: true
    background: false
    items:
      - 2022/08/2022-08-02-vivamus-vestibulum-ac-purus-at-pulvinar
      - 2022/10/2022-10-26-lorem-ipsum
      - 2023/02/2023-02-12-mauris-nibh-leo
    heading:
      title: 3 selected posts
      text: Duis nisl odio, blandit vel quam eget
  
  - type: selected-posts
    section: posts
    layout: list
    show_more: true
    background: false
    items:
      - 2022/08/2022-08-02-vivamus-vestibulum-ac-purus-at-pulvinar
      - 2022/10/2022-10-26-lorem-ipsum
      - 2023/02/2023-02-12-mauris-nibh-leo
    heading:
      title: 3 selected posts in list
      text: Duis nisl odio, blandit vel quam eget
  
  - type: selected-publications
    section: publications
    show_more: false
    background: true
    heading:
      surtitle: Lorem ipsum
      title: 1 selected publication
    items:
      - 2023/01/2023-01-12-sed-metus-quam-imperdiet-ut-enim-vitae
---
