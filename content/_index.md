---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD Scholar (Full-time)
          company: Department Of Chemistry, Graphic Era (Deemed to be University)
          company_url: https://geu.ac.in/
          company_logo: geu-logo
          location: Dehradun
          date_start: '2023-10-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Research & Development
              * Teaching Assitant
              * Experimentation
        - title: Research Assistant Intern
          company: Department Of Chemistry, Graphic Era (Deemed to be University)
          company_url: https://geu.ac.in/
          company_logo: geu-logo
          location: Dehradun
          date_start: '2022-07-01'
          date_end: '2023-08-31'
          description: |
              Responsibilities include:

              * Samples preparation
              * Summarize experiments results
              * Document procedures
        - title: Analytical Chemist Trainee
          company: CSIR-INDIAN INSTITUTE OF PETROLEUM 
          company_url: https://www.iip.res.in/
          company_logo: csir-logo
          location: Dehradun
          date_start: '2023-01-31'
          date_end: '2023-02-15'
          description: |
              Basic Skill Development Training on ‘Analytical Chemistry, Tools and Techniques’ 

              * Basics of analytical chemistry 
              * Qualitative and quantitative analysis : Pre-requisites
              * Various sample preparations
                  * Gravimetry
                  * Volumetry
                  * Physico-chemical characterization (including Petroleum analysis) 
              * Chromatography/Mass  Spectroscopy 
                ( GC, HPLC, GC-MS, LC-MS)
              * Spectroscopy (UV-Vis, FTIR,NMR) 
              * Diffraction and morphology, XRD/XRF
              * Analysis using ICP-AES/AAS, TGA, DTG
              * Figures of merit, Errors in analysis, validation. 
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         icon: coursera
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         icon: edx
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         icon: datacamp
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="photos" >}}
    design:
      columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: collection
  #   id: recent
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        "Feel free to reach out and connect with me professionally. Use the form below to share your thoughts, inquiries or opportunities. I look forward to hearing from you!"
      # Contact (add or remove contact options as necessary)
      email: adeebamirza.phd@geu.ac.in
      phone: 1800 270 1280
      appointment_url: 'https://calendly.com'
      address:
        street: 566/6, Bell Road, Society Area, Clement Town
        city: Dehradun
        region: Uttarakhand
        postcode: '248002'
        country: India
        country_code: IN
      directions: Enter the Campus through Gate No. 1 and walk a few steps, you will find Chemistry Lab behind CS/IT Block
      office_hours:
        - 'Monday - Friday'
        - '11:00 AM to 03:00 PM'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '30.268260767723373'
        longitude: '77.9943821418232'
      contact_links:
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'https://skype.com/en/'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
