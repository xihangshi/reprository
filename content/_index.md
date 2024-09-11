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
            size: cover
          position: right
          color: '#666'
                
     
      - title: 'Transverse Recoil Imprinted on Free-electron Radiation'
        content: '[Nature Communication(2024)](https://rdcu.be/dTrDC)'
        align: top
        background:
          image:
            filename: Picture1.jpg
            filters:
              brightness: 0.5
            size: contain
          position: top
          color: '#333'

      - title: 'Focused X-ray beam driven by Free Electrons'
        content: '[Light: Science & Applications(2023)](https://rdcu.be/dS66x)'
        align: top
        background:
          image:
            filename: Picture2.jpg
            filters:
              brightness: 0.5
            size: contain
          position: top
          color: '#333'

      - title: ' Tunable & Compact Free-electron X-ray Sources'
        content: '[Nature Photonics(2020)](https://doi.org/10.1038/s41566-020-0689-7)'
        align: top
        background:
          image:
            filename: Picture2.jpg
            filters:
              brightness: 0.5
            size: contain
          position: top
          color: '#333'

      - title: 'Superlight inverse Doppler effect'
        content: '[Nature Physics(2018)](https://doi.org/10.1038/s41567-018-0209-6)'
        align: top
        background:
          image:
            filename: Picture3.jpg
            filters:
              brightness: 0.5
            size: contain
          position: top
          color: '#333'    

  #      link:
  #        icon: graduation-cap
  #        icon_pack: fas
  #        text: Join Us
  #        url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: ture
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: markdown
    content:
      title: Research Interests
      subtitle:
      text: under construction
    design:
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
