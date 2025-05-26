---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: My Projects
      text:
      filters:
        folders:
          - project
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      count: 12
      pagination:
        enabled: true
        per_page: 12
    design:
      view: article-grid
      fill_image: false
      columns: 3
---
