---
title: Certificates
summary: Selected certifications and credentials
type: landing

cascade:
  - target:
      path: '{/certificates/*/**}'
    type: page
    params:
      show_breadcrumb: false

sections:
  - block: collection
    id: certificates
    content:
      title: Certificates
      subtitle: 'Validated skills spanning React Native, agentic AI, and Vertex AI.'
      filters:
        folders:
          - certificates
        exclude_current: true
    design:
      view: card
      show_read_time: false
      show_date: false
      show_read_more: true
      columns: 2
---
