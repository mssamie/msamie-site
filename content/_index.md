---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

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
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        I study self-assembly in soft-matter systems using coarse-grained molecular dynamics simulations. My work focuses on how amphiphilic polymers and surfactants organize into micelles, vesicles, and related morphologies, and how chain architecture, hydrophobicity, and molecular packing shape those pathways.

        Current projects use MARTINI-based models, GROMACS simulation workflows, VMD visualization, and Python/MDAnalysis post-processing to connect molecular-scale dynamics with experimentally relevant observables such as morphology evolution, diffusion, end-to-end distance distributions, and aggregate structure.

        I am especially interested in computational approaches that help explain polymer and surfactant self-assembly in systems connected to experimental characterization, including NMR DOSY and related soft-matter measurements.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
