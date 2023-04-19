---
# Leave the homepage title empty to use the site title
title:
date: 2023-04-18
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: abhishek
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas

  - block: experience
    id: industry
    content:
      title: Industry
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Engineer
          company: Washington University in St. Louis
          company_url: 'https://www.wustl.edu'
          company_logo: ''
          location: St. Louis, MO
          date_start: '2019-10-01'
          date_end: ''
          description: 

        - title: Device Integration Engineer
          company: RSA, The Security Division of EMC2
          company_url: 'https://www.rsa.com'
          company_logo: ''
          location: Bedford, MA
          date_start: '2010-05-01'
          date_end: '2012-08-30'
          description: 

        - title: Software Engineer
          company: Infosys Technologies Ltd.
          company_url: 'https://www.infosys.com'
          company_logo: ''
          location: Bangalore, Karnataka, India
          date_start: '2006-05-01'
          date_end: '2008-07-31'
          description: 
    design:
      columns: '2'

  - block: experience
    id: research
    content:
      title: Research
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Doctoral Researcher
          company: University of Massachusetts Amherst
          company_url: 'https://www.umass.edu'
          company_logo: ''
          location: Amherst, MA
          date_start: '2012-09-04'
          date_end: '2019-08-30'
          description: 

        - title: Research Intern
          company: Deutsche Telekom Silicon Valley Innovation Center
          company_url: 'https://www.t-mobile.com/labs'
          company_logo: ''
          location: Mountain View, CA
          date_start: '2015-05-10'
          date_end: '2015-09-28'
          description: 

        - title: Research Intern
          company: Deutsche Telekom Silicon Valley Innovation Center
          company_url: 'https://www.t-mobile.com/labs'
          company_logo: ''
          location: Mountain View, CA
          date_start: '2014-04-10'
          date_end: '2014-08-15'
          description: 
    design:
      columns: '2'

#   - block: portfolio
#     id: projects
#     content:
#       title: Projects
#       filters:
#         folders:
#           - projects
#       # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#       default_button_index: 0
#       # Filter toolbar (optional).
#       # Add or remove as many filters (`filter_button` instances) as you like.
#       # To show all items, set `tag` to "*".
#       # To filter by a specific tag, set `tag` to an existing tag name.
#       # To remove the toolbar, delete the entire `filter_button` block.
#       buttons:
#         - name: All
#           tag: '*'
#         - name: Deep Learning
#           tag: Deep Learning
#         - name: Other
#           tag: Demo
#     design:
#       # Choose how many columns the section has. Valid values: '1' or '2'.
#       columns: '1'
#       view: showcase
#       # For Showcase view, flip alternate rows?
#       flip_alt_rows: false

  - block: markdown
    content:
      title: Amateur Photography
      subtitle: ''
      text: |-
        {{< gallery album="portfolio" >}}
    design:
      columns: '1'

  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card

  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publications
        exclude_featured: true
    design:
      columns: '2'
      view: citation

#   - block: collection
#     id: talks
#     content:
#       title: Recent & Upcoming Talks
#       filters:
#         folders:
#           - event
#     design:
#       columns: '2'
#       view: compact

#   - block: tag_cloud
#     content:
#       title: Popular Topics
#     design:
#       columns: '2'
      
  - block: contact
    id: contact
    content:
      title: Contact Me
      subtitle:
      text:
      # Contact (add or remove contact options as necessary)
      appointment_url: 'https://calendly.com/abhishek-dwaraki'
      contact_links:
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
