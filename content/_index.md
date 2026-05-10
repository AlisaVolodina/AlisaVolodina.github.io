---
title: 'Home'
date: 2023-10-24
type: landing
sections:
  - block: resume-biography
    content:
      username: me
    design:
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
      avatar:
        size: medium
        shape: circle

  - block: collection
    id: projects
    content:
      title: "Мои проекты"
      filters:
        folders:
          - projects
      count: 2
    design:
      view: card
      columns: "2"

  - block: collection
    content:
      filters:
        folders:
          - blog
    design:
      spacing:
        padding: ['3rem', 0, '6rem', 0]
---   
