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
      buttons:
        - text: Personal Website
          icon: 
          url: https://fwxie.wordpress.com/
        - text: Selected Publications
          icon: 
          url: https://fwxie.com/publications/
        - text: Google Scholar
          icon: brands/google-scholar
          url: https://scholar.google.com/citations?user=ZMSsT_gAAAAJ
        - text: Review article on alginate-based materials
          icon: 
          url: https://doi.org/10.1016/j.mser.2024.100799
---
