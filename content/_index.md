---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
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
        - name: Molecular biology
          icon: dna
          icon_pack: fab
        - name: Fungi
          icon: mushroom
          icon_pack: fas
        - name: Football
          icon: futbol
          icon_pack: fas
  - block: experience
    content:
     title: Education
      subtitle:

      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006

      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      experience:
        - title: 'PhD in Biological Sciences'
          company: 'University of Auckland'
          company_url: 'https://www.auckland.ac.nz/en.html'
          company_logo: uoa-logo
          location: 'Tāmaki Makaurau, Auckland'
          date_start: '2020-10-01'
          date_end: ''
          description: >-
          * Functional characterisation of virulence genes in the fungal pathogen of apple *Neonectria ditissima*
              
        - title: 'MSc in Biological Sciences'
          company: 'University of Auckland'
          company_url: 'https://www.auckland.ac.nz/en.html'
          company_logo: uoa-logo
          location: 'Tāmaki Makaurau, Auckland'
          date_start: '2017-07-01'
          date_end: '2019-06-30'
          description: >-
          * Identification of virulence genes in the fungal pathogen of apple *Neonectria ditissima*

        - title: 'BSc in Biology'
          company: 'Universidad Peruana Cayetano Heredia'
          company_url: 'https://www.cayetano.edu.pe/cayetano/es/'
          company_logo: cayetano-logo
          location: 'Lima, Peru'
          date_start: '2011-03-01'
          date_end: '2015-12-01' 

      design:
        columns: '2
---
