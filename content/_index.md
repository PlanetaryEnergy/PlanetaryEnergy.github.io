---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Planetary Energy Laboratory
        content: Optimization for a sustainable tomorrow 🌍
        align: left
        background:
          image:
            filename: offshore_wind.jpg
            filters:
              brightness: 0.8
          position: center
          color: '#666'
        link:
          text: Research Fields
          url: ./field
      - title: Energy-Resource Assessment Model (E-RAM)
        content: The E-RAM model assesses various resource potential related to energy.
        align: left
        background:
          image:
            filename: eram.jpg
            filters:
              brightness: 0.5
          position: right
          color: '#666'
        link:
          text: Details
          url: ./model/eram
      - title: China Integrated Sustainable Power-system Optimization Model (CISPO)
        content: The CISPO model is a long-term power-system planning model for China.
        align: left
        background:
          image:
            filename: cispo.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#555'
        link:
          text: Details
          url: ./model/cispo
      - title: Global Integrated Sustainable Power-system Optimization Model (GISPO)
        content: The GISPO model is a long-term power-system planning model for the whole world.
        align: left
        background:
          image:
            filename: gispo.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          text: Details
          url: ./model/gispo
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: hero
    content:
      title: 
      image:
        filename: pel.png
      text: 星源（Planetary Energy）致力于探索可再生能源发展和新型电力系统建模分析，重点推进交叉学科研究，深入分析全国和全球电力系统转型路径中的关键科学问题。
  
  - block: collection
    content:
      title: 最新动态
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: collection
    content:
      title: 最新成果
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Join the team →" %}}
    design:
      columns: '1'
---
