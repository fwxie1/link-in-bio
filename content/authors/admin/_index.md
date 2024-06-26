---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      sections:
        - heading: Websites
          buttons:
            - text: Personal Website
              icon: ''
              url: https://fwxie.wordpress.com/
            - text: University of Bath Research Portal Profile
              icon: ''
              url: https://researchportal.bath.ac.uk/en/persons/david-fengwei-xie
        - heading: Research & Publications
          buttons:  # Corrected indentation
            - text: Research
              icon: ''
              url: https://fwxie.wordpress.com/Research/
            - text: Selected Publications
              icon: ''
              url: https://fwxie.wordpress.com/publications/
            - text: Google Scholar
              icon: brands/google-scholar
              url: https://scholar.google.com/citations?user=ZMSsT_gAAAAJ
            - text: ResearchGate
              icon: academicons/researchgate
              url: https://www.researchgate.net/profile/Fengwei-Xie
        - heading: Recent Publications
          buttons:  # Corrected indentation
            - text: Review article on alginate-based materials
              icon: ''
              url: https://doi.org/10.1016/j.mser.2024.100799
---
