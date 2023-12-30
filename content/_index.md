---
# Leave the homepage title empty to use the site title
title: Shengyuan's Website
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
  - block: experience
    id: experience
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
    
        - title: Master of Research
          company: Imperial College London
          company_url: 'https://www.imperial.ac.uk/neurotechnology/'
          company_logo: imperial
          location: London, United Kingdom
          date_start: '2023-09-30'
          description: |2-
              * **Major:** Neurotechnology
              * **Academic Supervisor:** Dr. Simon Schultz
              * **Relevant Projects:** Graph-theoretic analysis of memory encoding and recall with application to dementia.
    
        - title: Research Assistant
          company: Southern University of Science and Technology
          company_url: 'https://www.sustech.edu.cn'
          company_logo: sustech
          location: Shenzhen, China
          date_start: '2022-02-09'
          date_end: '2023-09-15'
          description: |2-
              * **Supervisor:** Dr. Quanying Liu (https://faculty.sustech.edu.cn/?tagid=liuqy&lang=en)
              * **Research Focus:** Finding effective connectivity in the non-linear information flow of asynchronous fMRI data, Analyzing brain heterogenous development to detect functional emergence in preterms and terms

        - title: Undergraduate Research Assistant
          company: Chinese Academy of Sciences - Shenzhen Institute of Advanced Technology
          company_url: 'http://english.siat.cas.cn/'
          company_logo: SIAT
          location: Shenzhen University Town, Shenzhen, China
          date_start: '2023-01-20'
          date_end: '2022-08-30'
          description: |2-
              * **Supervisor:** Dr. Pengfei Wei (https://jechenlab.com/)
              * **Research Focus:** Human Cerebral Cortex Organization Estimated by Functional PET-FDG "Metabolic Connectivity"
    
        - title: Undergraduate Research Assistant
          company: Lehigh university
          company_url: 'http://yuzhangresearch.weebly.com/'
          company_logo: Lehigh
          location: Bethlehem, PA, United States
          date_start: '2021-08-10'
          date_end: '2021-03-10'
          description: |2-
              * **Supervisor:** Dr. Yu Zhang  (https://engineering.lehigh.edu/faculty/yu-zhang)
              * **Research Focus:** Implementation of brain-computer interface algorithm with different distraction paradigms
    
        - title: Undergraduate
          company: Shandong university
          company_url: 'https://brain.sdu.edu.cn/en/About/Introduction.htm'
          company_logo: sdu
          location: Jinan, Shandong, China
          date_start: '2022-06-10'
          date_end: '2018-09-10'
          description: |2-
              * **Major:** Electrical and Information Engineering, Innovation Key Class
              * **Academic Supervisor:** Dr. Qiang Wu (https://brain.sdu.edu.cn/en/info/1090/1115.htm)
              * **GPA:** 87/100
              * **Designed a graph convolutional neural network with the self-attention mechanism for graph feature analysis
              * Outstanding Bachelor thesis (top 1%)
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      default_button_index: 0

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
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-

      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: tag_cloud
    id: topics
    content:
      title: Topics
    design:
      columns: '2'
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
  - block: accomplishments
    id: accomplishments
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
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="my_album" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: s.cai23@imperial.ac.uk
      appointment_url: 'https://calendly.com/shengyuan'
      contact_links:
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://imperial-ac-uk.zoom.us/j/98536867915?pwd=RTVWc2NLSEZ0RmQya1E5ZFN0M2dmZz09'
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
