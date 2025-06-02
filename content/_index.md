---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
- block: collection
  id: publications
  content:
    title: Recent Publications
    page_type: post
    count: 0  # чтобы показать все посты
    filters:
      author: ""
      category: ""
      tag: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      publication_type: ""
    offset: 0
    order: desc
  design:
    view: date-title-summary
    spacing:
      padding: [0, 0, 0, 0]
---