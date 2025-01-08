---
title: Gallery
# summary: My courses
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: gallery
    content:
      title: Gallery
      filters:
        folders:
          - gallery
    design:
      view: article-grid
      columns: 2
---
