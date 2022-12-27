---
# Leave the homepage title empty to use the site title
title:
date: 2022-12-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: 90%
          icon: python
          icon_pack: fab
        - name: SQL
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Java
          description: 80%
          icon: java
          icon_pack: fab
        - name: Hive
          description: 90%
          icon: hive
          icon_pack: fab
        - name: Linux
          description: 100%
          icon: linux
          icon_pack: fab
        - name: Kaggle
          description: 100%
          icon: kaggle
          icon_pack: fab
        - name: Git
          description: 80%
          icon: git
          icon_pack: fab
        - name: Docker
          description: 80%
          icon: docker
          icon_pack: fab
        - name: Github
          description: 80%
          icon: github
          icon_pack: fab
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

        - title: Senior Software Engineer
          company: HSBC
          company_url: ''
          company_logo: hsbc
          location: GuangZhou
          date_start: '2023-08-07'
          date_end: '2024-01-01'
          description: |2-
              Responsibilities include:

              * Data Modelling
              * Data Warehousing
              * Data Security

        - title: Senior Software Engineer
          company: HSBC
          company_url: ''
          company_logo: hsbc
          location: GuangZhou
          date_start: '2022-08-06'
          date_end: '2022-12-06'
          description: |2-
              Responsibilities include:

              * Data Modelling
              * Data Warehousing
              * Data Security

          - title: Senior Software Engineer
          company: HSBC
          company_url: ''
          company_logo: hsbc
          location: GuangZhou
          date_start: '2021-08-05'
          date_end: '2022-08-05'
          description: |2-
              Responsibilities include:

              * Data Modelling
              * Data Warehousing
              * Data Security

        - title: Data Engineer
          company: SRCB
          company_url: ''
          company_logo: srcb
          location: ShenZhen
          date_start: '2020-07-01'
          date_end: '2021-07-25'
          description: |2-
              Responsibilities include:

              * Data Modelling
              * Data Warehousing
              * Data Reporting
        

        

        

    design:
      columns: '3'
  
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
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
      columns: '2'
 
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: 740583913@qq.com
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

---
