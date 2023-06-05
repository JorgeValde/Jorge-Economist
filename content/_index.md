---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Economist
          company: Latin American Steel Association (ALACERO)
          location: Santiago, Chile
          date_start: '2014'
          date_end: '2017'
          Responsibilities include:
                Data gathering and analysis for policy reports
              
        - title: Technical Secretary for the Economics and Institutional Relations Committee (CERIN)
          company: Latin American Steel Association (ALACERO)
          location: Santiago, Chile
          date_start: '2015'
          date_end: '2017'
          Responsibilities include:
                Consolidated and presented the Latin American Steel Consumption Outlook (SRO) 
    design:
      columns: '2'
  
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
       
      # Contact (add or remove contact options as necessary)
      email: javaldeb@syr.edu
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
      columns: '2'
---
