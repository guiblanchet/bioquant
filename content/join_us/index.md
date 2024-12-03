---
title: Join us
date: 2024-2-07

type: landing

sections:
  - block: join_us
    content:
      title: Join us
      text: |-
        If you want to join this wonderful lab, you need to swim in a 0° river.
      # email: guillaume.blanchet@usherbrooke.ca
      # phone: 
      # address:
      #   street: 2500 Bd de l'Université
      #   city: Sherbrooke
      #   region: QC
      #   postcode: 'J1K2R1'
      #   country: Canada
      #   country_code: CA
      # coordinates:
      #   latitude: '45.38042'
      #   longitude: '-71.92555'
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      # appointment_url: 'https://calendly.com'
      # contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: icon.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
