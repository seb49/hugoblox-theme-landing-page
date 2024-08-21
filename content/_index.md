---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Ecouflant Club Badminton
      text: Rejoignez le club !
      # primary_action:
      #   text: Get Started
      #   url: https://hugoblox.com/templates/
      #   icon: rocket-launch
      # secondary_action:
      #   text: Read the docs
      #   url: https://docs.hugoblox.com
      # announcement:
      #   text: "Inscriptions bientôt"
      #   link:
      #     text: "(cliquez ici)"
      #     url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          #filename: bg-triangles.svg
          filename: bad.png
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "1998"
          description: |
            Date de création du club
        - statistic: "365"
          description: |
            Licencié(e)s  
            depuis 1998
        - statistic: "50%"
          description: |
            50% de femmes        
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: creneaux
    content:
      title: Créneaux
      #text: Build your site with blocks 🧱
      items:
        - name: Mardi
          icon: clock
          description: mardi de 19h30 à 22h30
        - name: Samedi
          icon: clock
          description: samedi du 10h00 à 12h45.
  - block: simpletext
    id: evenement
    content:
      title: Evènements à venir
      #text: Build your site with blocks 🧱
      items:
        - name: Mardi
          icon: clock
          description: mardi de 19h30 à 22h30
        - name: Samedi
          icon: clock
          description: samedi du 10h00 à 12h45.
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: gallery
    id: gallery
    content:
      title: Gallerie
      #text: Build your site with blocks 🧱
      images:
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4d4396c9e.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4d464bf4b.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4d446521a.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4d457972c.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4e628daa1.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4e634f5a3.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4e62d88fb.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4e6307c8c.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4e637a57d.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4e61730bf.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4e632d887.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4e632d05b.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4e634f5d4.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4e62b0275.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4f0abbfbf.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4f0a7a453.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4f09ee2e6.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4f094cc1f.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4f0a88ef5.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4f0b24ae2.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4f0a4e62a.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4f0b5435d.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4f0b1187e.jpg
        - src: https://images.cdn-files-a.com/uploads/8485186/2000_64ff4f0b188f5.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: inscription
    content:
      title: Inscription
      text: Formulaire d'inscription saison 2023-2024
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Build your future-proof website
          text: As easy as 1, 2, 3!
          feature_icon: check
          features:
            - "Future-proof - edit your content in text files"
            - "Website is generated by a single app, Hugo"
            - "No JavaScript knowledge required"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Get Started
            url: https://hugoblox.com/templates/
        - title: Large Community
          text: Join our large community on Discord - ask questions and get live responses
          feature_icon: bolt
          features:
            - "Dedicated support channel"
            - "3,000+ users on Discord"
            - "Share your site and get feedback"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Join Discord
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  # - block: testimonials
  #   content:
  #     title: ""
  #     text: ""
  #     items:
  #       - name: "Hugo Smith"
  #         role: "Marketing Executive at X"
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: "testimonial-1.jpg"
  #         text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
  #   design:
  #     spacing:
  #       # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #       padding: ["6rem", 0, 0, 0]
  # - block: cta-card
  #   content:
  #     title: Build your future-proof website
  #     text: As easy as 1, 2, 3!
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
