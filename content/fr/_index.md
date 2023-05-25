---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: apropos
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # text:
      # Je suis développeur pour la science ouverte en archéologie au [LAMPEA](https://lampea.cnrs.fr), à la [MMSH](https://mmsh.fr) d'Aix-en-Provence, et enseignant en cartographie au sein du [Master Urba](https://master-urbanisme.www.univ-montp3.fr/fr/%C3%A9quipe/equipe-et-fonctionnement-p%C3%A9dagogique) de l'Université Paul Valéry à Montpellier. Je suis également le [créateur](https://mapper.fr/carnet/introducing-mapstodon/) de [mapstodon.space](https://mapstodon.space), une instance Mastodon multilingue dédiée à la cartographie qui rassemble aujourd'hui environ un millier de personnes. Je suis disponible pour réaliser des prestations [autour de la cartographie et de l'open data](https://mapper.fr/carnet/ips-geolocalise/) - [n'hésitez pas à me contacter](https://mapper.fr/#contact)!
    # design:
    #   background:
    #     color: black
    #     text_color_light: true
    #     image:
    #       # Add your image background to `assets/media/`.
    #       filename: li-yang-5h_dMuX_7RE-unsplash.webp
    #       filters:
    #         brightness: 0.5
    #       size: cover
    #       position: center
    #       parallax: false
  # - block: markdown
  #   content:
  #     title: 'Welcome 👋'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.
  #
  #       **Specialties:** Analytics & Data, Leadership, Programming, Strategic Planning, Writing & Editing
    # design:
    #   columns: '1'
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '1'
---
