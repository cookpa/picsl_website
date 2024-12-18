---
# Display name
title: James Gee

# Name pronunciation (optional)
name_pronunciation:

# Full name (for SEO)
first_name: James
last_name: Gee

user_groups:
    - Principal Investigators

# Status emoji
# status:
#   icon: ''

# Is this the primary user of the site?
superuser: false

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: Director

username: jimgee

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: PICSL
    url: https://picsl.upenn.edu
  - name: GRASP lab
    url: https://www.grasp.upenn.edu
  - name: Department of Radiology
    url: https://www.pennmedicine.org/departments-and-centers/department-of-radiology
  - name: Institute for Translational Medicine and Therapeutics
    url: https://www.itmat.upenn.edu

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto: lastname (at nospam) upenn (dot) edu'
    label: E-mail Me
 # - icon: brands/x
 #   url: https://twitter.com/rohitrango
  # - icon: brands/instagram
  #   url: https://www.instagram.com/
#   - icon: brands/github
#     url: https://github.com/rohitrango
#   - icon: brands/linkedin
#     url: https://www.linkedin.com/in/rohitrango
  - icon: academicons/google-scholar
    url: https://scholar.google.com/citations?user=MIjWr_8AAAAJ
  - icon: academicons/orcid
    url: https://orcid.org/0000-0002-2258-0187

interests:
  - Computer Science
  - Bioengineering
  - Radiology

# fill this in later
# education:

#   - area: PhD Artificial Intelligence
#     institution: University of Pennsylvania
#     date_start: 2021-05-20
#     date_end: 2027-05-15
#     summary: |
#       Towards feature-aware deformable registration and unbiased evaluation.
#     # button:
#     #   text: 'Webpage'
#     #   url: 'https://jenaroh.it'

#   - area: Masters in Robotics
#     institution: Carnegie Mellon University
#     date_start: 2019-08-20
#     date_end: 2021-05-15
#     summary: |
#       GPA: 4.13/4.0

#       Masters Thesis: "Learning Mental Models of Experts in a Simulated Search and Rescue Scenario"
#     button:
#       text: Thesis PDF
#       url: https://www.ri.cmu.edu/app/uploads/2021/08/cmu_msr_thesis.pdf

#   - area: BTech in Computer Science and Engineering
#     institution: Indian Institute of Technology, Bombay
#     date_start: 2015-07-20
#     date_end: 2019-05-15
#     summary: |
#       GPA: 9.56/10.0

#       Courses included:
#       - Machine Learning
#       - Data Structures and Algorithms
#       - Computer Vision
#       - Operating Systems
#       - Computer Networks

#       Undergraduate Thesis: "Perfect Sampling and Uncertainty Estimation in Deep Networks"

# work:
# - position: Deep Learning Research Intern
#     company_name: NVIDIA
#     company_url: ''
#     company_logo: ''
#     date_start: 2024-05-20
#     date_end: '2024-09-06'
#     summary: |2-
#     Alignment for text-to-image diffusion models

# - position: Applied Scientist Intern
#     company_name: Amazon Lab 126
#     company_url: ''
#     company_logo: ''
#     date_start: 2022-05-20
#     date_end: 2022-08-20
#     summary: |
#     Mesh-NeRF/3DGS hybrid models for human avatar recovery

# # Skills
# # Add your own SVG icons to `assets/media/icons/`
# skills:
#   - name: Technical Skills
#     items:
#       - name: Python
#         description: ''
#         percent: 80
#         icon: code-bracket
#       - name: Data Science
#         description: ''
#         percent: 100
#         icon: chart-bar
#       - name: SQL
#         description: ''
#         percent: 40
#         icon: circle-stack
#   - name: Hobbies
#     color: '#eeac02'
#     color_border: '#f0bf23'
#     items:
#       - name: Hiking
#         description: ''
#         percent: 60
#         icon: person-simple-walk
#       - name: Cats
#         description: ''
#         percent: 100
#         icon: cat
#       - name: Photography
#         description: ''
#         percent: 80
#         icon: camera

# languages:
#   - name: English
#     percent: 100
#   - name: Hindi
#     percent: 90
#   - name: Odia
#     percent: 90

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
# awards:

#   - title: Neural Networks and Deep Learning
#     url: https://www.coursera.org/learn/neural-networks-deep-learning
#     date: '2023-11-25'
#     awarder: Coursera
#     icon: coursera
#     summary: |
#       I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.

type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      title: "Welcome"
      username: jimgee
      # Show a call-to-action button under your biography? (optional)
    #   button:
    #     text: Download CV
    #     url: uploads/rohit-resume.pdf
    design:
      css_class: dark
      background:
        color: system
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1
          size: cover
          position: center
          parallax: true

<!-- This text will go on top of the file, checkout the reference image -->
Professor Gee's major area of interest is biomedical image analysis and computing, with active research in quantitative methods including segmentation, registration, morphometry and shape statistics. He is interested in the study of all organ systems using both established and emerging imaging modalities and biological/biomaterials imaging as well as in vivo medical imaging.


  ## whatever else you want to add
  # - block: markdown
  #   content:
  #     title: More about me 👀
  #     text: |-
  #       lorem ipsum dolor sit amet consectetur adipiscing elit sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident sunt in culpa qui officia deserunt mollit anim id est laborum.

  ## If you want to show off your skills
  # - block: resume-experience
  #   content:
  #     # Choose a user profile to display (a folder name within `content/authors/`)
  #     title: "Welcome"
  #     username: rohitjena

  ## If you want to show awards
  # - block: resume-awards
  #   content:
  #     # Choose a user profile to display (a folder name within `content/authors/`)
  #     title: "Awards"
  #     username: rohitjena

---