---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '🚀 Agentic Mobile Systems'
      subtitle: ''
      text: |-
        I help founders and product teams ship resilient cross-platform apps and pragmatic agentic AI copilots. Every engagement includes a measurable performance baseline, modular architecture, and an enablement plan so your team keeps shipping after handoff.

        - **React Native performance engineering** — New Architecture adoption, Expo/CLI hybrid workflows, and CI/CD automation with Bitrise/GitHub Actions.
        - **Agentic AI copilots** — LangGraph and OpenAI Agents SDK pipelines with evaluation harnesses, guardrails, and analytics so humans stay in control.
        - **Product leadership** — translating KPIs into roadmaps, aligning design systems, and coaching engineers through observability, testing, and release cadences.

        Let’s build something dependable together. Reach me at [hassanjamil91@gmail.com](mailto:hassanjamil91@gmail.com) or **[+971 58 977 6893](https://api.whatsapp.com/send/?phone=971589776893&text&type=phone_number&app_absent=0)**.
    design:
      columns: '1'
  - block: resume-experience
    content:
      title: Delivery Highlights
      username: admin
    design:
      date_format: 'Jan 2006'
      is_education_first: false
  - block: collection
    id: featured-projects
    content:
      title: Featured Projects
      text: 'A snapshot of the production apps and SDKs I have recently delivered.'
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 3
  - block: collection
    id: blog
    content:
      title: Latest Writing
      subtitle: ''
      text: 'Notes on React Native, agentic AI adoption, and shipping culture.'
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    content:
      title: Ready to ship your next release faster?
      text: |-
        I partner with teams to audit their mobile experiences, build agentic copilots, and coach engineers through adoption. Share a brief about your roadmap and I'll send a lightweight plan within 48 hours.
      button:
        text: Schedule a meet
        url: mailto:hassanjamil91@gmail.com
    design:
      card:
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
