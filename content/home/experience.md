---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
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
  - title: Software Engineer Intern
    company: Disney+ Hotstar
    company_url: ''
    company_logo: DP-Hotstar
    location: Beijing, China
    date_start: '2021-04-05'
    date_end: ''
    
    description: |2-
        <img src="uploads/DP-Hotstar.jpeg" alt="UCSD" width="700" height="300"/>

        # <font size="6">Experience Description</font> 
        * Improved implementations for anomaly detection in time series data using **Facebook Prophet**, proposed reasons behind error, and finally clustered hypotheses using Disjoint-set in **Golang**.
        * Built a **Docker Kubernetes-ready** Service in **Golang** which managed to aggregate and standardize metrics from different external sources dynamically, thereby supporting monitoring multiple servers with **Prometheus and Grafana**.

  - title: Software Engineer Intern
    company: Listening to Waves | University of California, San Diego
    company_url: ''
    company_logo: UCSD
    location: San Diego, CA
    date_start: '2020-09-27'
    date_end: '2021-01-28'
    
    description: |2-
        <img src="uploads/UCSD-JSOE-2.jpeg" alt="UCSD" width="700" height="300"/>

        # <font size="6">Experience Description</font> 
        * Designed and implemented an **user-interactive** canvas which generate complex audio waveforms based the userinput, thus helping **500+** customers experience the art of electronic music and visualize some common signals.
        * Fixed pure and complex waves’ frequency and period mismatching in responsive design, thereby helping more **500+** users understand the relation between frequency and period correctly with **CI/CD pipeline** in CodeDeploy.

  - title: Academic Tutor/Teaching Assistant
    company: University of California, San Diego
    company_url: ''
    company_logo: UCSD
    location: San Diego, CA
    date_start: '2020-03-27'
    date_end: '2020-03-28'
    
    description: |2-
        <img src="uploads/UCSD-3.jpeg" alt="UCSD" width="700" height="300"/>

        # <font size="6">Experience Description</font> 
        * Served as an **undergraduate teaching assistant** for DSC30/DSC20 with **200+** students enrolled, held **100+** office hours to guide students with **Java, Python, Data Structure, and Algorithms**.
        * Took responsibilities of helping with discussion sections, assisting students in **programming assignments**, crafting conceptual and algorithmic questions for midterms/finals, and grading programs and exams.
        * Explained **Data Structure and Algorithm** including searching algorithms, linked lists, queues, heaps, graphtraversal, trees, huffman coding, hash tables, and object-oriented programming.




  # - title: Professor of Semiconductor Physics
  #   company: University X
  #   company_url: ''
    # company_logo: org-x
    # location: California
    # date_start: '2016-01-01'
    # date_end: '2020-12-31'
    # description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---
