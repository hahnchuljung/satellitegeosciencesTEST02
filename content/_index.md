---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: SATELLITE GEOSCIENCES LAB
      image:
        filename: '' # hero-academic.png
      # cta:
        # label: '**Get Started**'
        # url: https://wowchemy.com/templates/
      # cta_alt:
        # label:  Ask a question
        # url: https://discord.gg/z8wNYzb
      # cta_note:
        # label:  >-
      text: |-
       <font size="5">  DEPT. EARTH SYSTEM SCIENCES YONSEI UNIVERSITY </font> <br />
       <font size="3">  연세대학교 위성지구과학 연구실 홈페이지에 방문하신 것을 환영합니다 </font>
        # <!--Custom spacing-->
        # <div class="mb-3"></div>
        # <!--GitHub Button JS-->
        # <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
      
        
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
       My research interests include remote sensing, water resources, natural disaster monitoring.
       
       The lab's doors are always open to PhD, MSc, and undergraduate students looking for research topics. Please feel free to visit us to learn more about possible research topics and programs.
       
    design:
      columns: '2'



  - block: experience
    id: experience
    content:
      title: Professional Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assocaite Professor
          company: Dept. of Earth System Sciences, Yonsei University
          company_url: 'http://geo.yonsei.ac.kr/en/'
          company_logo: school
          location: Seoul, Korea
          date_start: '2023-03-01'
          date_end: 
          description: Taught satellite geosciences and satellite hydrology
        - title: Joint Associate Professor
          company: University of Science & Technology (UST), Ocean Science and Technology (OST) 
          company_url: 'https://www.ust.ac.kr/eng.do'
          company_logo: school
          location: Busan, Korea
          date_start: '2021-03-01'
          date_end: '2023-02-28'
          description: Taught costal remote sensing
        - title: Senior Rserach Scientist
          company: Korea Ocean Satellite Center, Korea Institute of Ocean Science and Technology (KIOST)
          company_url: 'https://kosc.kiost.ac.kr/index.nm?lang=en&contentId=82'
          company_logo: research
          location: Busan, Korea
          date_start: '2020-03-13'
          date_end: '2023-02-28'
          description: |2-
              * Spatio-temporal variability of coastal wetlands using Synthetic Aperture Radar
              * Development of satellite-based system on monitoring and predicting ship distribution in the contiguous zone 
        - title: Lead & Chief Research Scientist
          company: NASA Goddard Space Flight Center (GSFC) & Science Systems and Applications, Inc (SSAI)
          company_url: 'https://science.gsfc.nasa.gov/earth/hydrology/'
          company_logo: satellite
          location: Maryland, USA
          date_start: '2015-01-05'
          date_end: '2020-03-06'
          description: |2-
              * A west Africa LDAS for forecasting extreme hydrological Events
              * Water balance and resource studies using satellite observations 
              * Radar flood mapping
              * Land Information System (LIS) modeling         
        - title: Research Associate
          company: NASA Goddard Space Flight Center (GSFC) & University of Maryland (UMD)
          company_url: 'https://science.gsfc.nasa.gov/earth/hydrology/'
          company_logo: satellite
          location: Maryland, USA
          date_start: '2014-01-31'
          date_end: '2015-01-04'          
          description: |2-
              * Radar application on ecosystem and hazard
              * CREST hydrological model
        - title: Postdoctoral Researcher
          company: NASA Goddard Space Flight Center (GSFC) & Oak Ridge Associated Universities (ORAU)
          company_url: 'https://science.gsfc.nasa.gov/earth/hydrology/'
          company_logo: satellite
          location: Maryland, USA
          date_start: '2011-01-07'
          date_end: '2014-01-06'          
          description: |2-
              * Interferometric SAR application to wetland 
              * 2D floodplain hydrodynamic LISFLOOD model         
    design:
      columns: '2'
      
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
      
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
      
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
 
# - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'

# - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card

# - block: collection
#    content:
#      title: Recent Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation

# - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
      
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
      
  - block: pulbication
    id: publication
    content:
      title: Contact
      subtitle:
      email: Google Scholar
    design:
      columns: '2'      
      
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
 #     text: |-
 #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: hahnchul.jung@yonsei.ac.kr
      phone: +82-2-2123-2677
#      appointment_url: 'https://calendly.com'
      address:
        street: 50 Yonsei-ro
        city: Seodaemun-gu
        region: Seoul
        postcode: '03722'
        country: South Korea
        country_code: KR
      directions: Science Hall Rm. 645, College of Science, Yonsei University
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
#      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
#          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
    design:
      columns: '2'
---
