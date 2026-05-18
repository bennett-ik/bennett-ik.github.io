---
title: ''
summary: ''
date: 2024-03-01
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My work focuses on three interconnected areas: **electrochemical furfural oxidation** for biomass valorization, **catalyst design** (single-atom and perovskite-structured materials), and **solar-driven electrochemistry** via perovskite solar cell-based PEC/PVEC systems. I am interested in understanding how atomic-scale structure governs catalytic activity and selectivity.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
        featured_only: false
    design:
      view: citation

  - block: contact
    id: contact
    content:
      title: Contact
      email: ig0326@unist.ac.kr
      city: Ulsan
      country: South Korea
    design:
      columns: '1'
---
