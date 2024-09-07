---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-07
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: "<span style='font-size: 48px;'>Welcome to the Research Page</span>"
        content: "<span style='font-size: 24px;'>My research covers the entire spectrum from the fundamental all the way to the very applied. In particular, we strive to deepen our understanding of quantum science in the field of free-electron-light interactions and make use of it.</span>"
        align: center
        background:
          image:
            filename: homepage1.jpg
            filters:
              brightness: 0.4
          position: right
          color: '#666'
          css_class: "padding: 20px;"
      
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: collection
    content:
      title: Research Interest
      text: "Under construction"
      count: 
      filters:
        folders:
          -       
    design:
      view: list
      columns: '1'     
  
  - block: collection
    content:
      title: Latest publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: list
      columns: '1'     
---
