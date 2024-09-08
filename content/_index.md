---
# Leave the homepage title empty to use the site title
title: "Junjue Liao"
date: 2024-09-07
type: landing

design:
  # Default section spacing
  spacing: "2.2rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: /uploads/resume.pdf
    design:
      css_class: light
      background:
        color: white
        #image:
        #  # Add your image background to `assets/media/`.
        #  filename: stacked-peaks.svg
        #  #filename: white.png
        #  filters:
        #    brightness: 1.0
        #  size: cover
        #  position: center
        #  parallax: false
  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: Mainly fun theoretical works. All the work is being sorted out now to be published.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: true
      columns: 3

  - block: resume-experience
    id: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'September 2024'
      # Education or Experience section first?
      is_education_first: false
---
