---
# Leave the homepage title empty to use the site title
title: Shengyuan's Website
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
  - block: collection
    id: news
    content:
      title: News
      filters:
        folders:
          - news
      text: |-
        12-07-2024 | Project: [Matching_graphs_spatial_constraints](https://www.logml.ai/projects/Anna-Calissano.html). LOGML Summer School, London Geometry and Machine Learning
    
        28-06-2024 | I will be presenting my [poster](uploads/Shengyuan%20Poster.pdf) at the neurotechnology symposium, Imperial College London.
    
        10-09-2021 | I received financial support from [National Training Programs of Innovation and Entrepreneurship](http://gjcxcy.bjtu.edu.cn/NewLXItemListForStudentDetail.aspx?ItemNo=862572&year=2021&type=student&IsLXItem=0/), which inspired me to continue to carry out my research!
    
        11-07-2021 | I attended [Neuromatch](https://portal.neuromatchacademy.org/certificate/85beff50-f5f0-477a-ab22-ab3fd0b57288), very happy to learn computational neuroscience with my friends!
    
        02-07-2020 | I attended the summer semester of [Peking University](https://www.oir.pku.edu.cn/summerschool/) and learned FPGA design based on the RISC-V framework.
    design:
      columns: '2'
    
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: citation
    
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
        - name: Neurobehavior
          tag: Neurobehavior
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
    
  - block: tag_cloud
    id: topics
    content:
      title: Topics
    design:
      columns: '2'
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
    
  #- block: accomplishments
    #id: accomplishments
    #content:
      ## Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      #title: 'Accomplish&shy;ments'
      #subtitle:
      #date_format: Jan 2006

      #items:
        
    #design:
      #columns: '2'
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
              * **Supervisor:** Dr. Quanying Liu
              * **Research Focus:** Finding effective connectivity in the non-linear information flow of asynchronous fMRI data, Analyzing brain heterogenous development to detect functional emergence in preterms and terms

        - title: Undergraduate Research Assistant
          company: Chinese Academy of Sciences - Shenzhen Institute of Advanced Technology
          company_url: 'http://english.siat.cas.cn/'
          company_logo: SIAT
          location: Shenzhen, China
          date_start: '2022-08-30'
          date_end: '2023-01-20'
          description: |2-
              * **Supervisor:** Dr. Pengfei Wei
              * **Research Focus:** Inferring the relationship between neural activity and episodic behavior under the influence of sepsis.
        - title: Undergraduate Research Assistant
          company: Lehigh university
          company_url: 'http://yuzhangresearch.weebly.com/'
          company_logo: Lehigh
          location: Bethlehem, PA, United States
          date_start: '2021-03-10'
          date_end: '2021-08-10'
          description: |2-
              * **Supervisor:** Dr. Yu Zhang
              * **Research Focus:** Implementation of brain-computer interface algorithm with different distraction paradigms
        - title: Undergraduate
          company: Shandong university
          company_url: 'https://brain.sdu.edu.cn/en/About/Introduction.htm'
          company_logo: sdu
          location: Jinan, Shandong, China
          date_start: '2018-09-10'
          date_end: '2022-06-10'
          description: |2-
              * **Major:** Electrical and Information Engineering, Innovation Key Class
              * **Academic Supervisor:** Dr. Qiang Wu
              * **GPA:** 87/100
              * Designed a graph convolutional neural network with the self-attention mechanism for graph feature analysis
              * Outstanding bachelor thesis (top 1%)
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
      # coordinates:
        # latitude: '51.4988'
        # longitude: '-0.176894'
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'  
---
