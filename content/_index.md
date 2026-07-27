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
        I use coarse-grained molecular dynamics to study how amphiphilic polymers organize into micelles, vesicles, and related soft-matter structures. My published work examines the formation of vesicles from BAB triblock copolymers in water, connecting molecular reorganization and chain conformations to a sequence of transient aggregate structures.

        My computational toolkit includes GROMACS, MARTINI models, VMD, Python, and MDAnalysis. This site highlights peer-reviewed results and research materials cleared for public sharing.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publication
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
---
