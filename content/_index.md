---
# Leave the homepage title empty to use the site title
title:
date: 2025-02-07
type: landing

sections:
  - block: hero
    content:
      title: |
        Welcome to the BAB Lab!
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Boreal-Arctic Biogeochemistry** lab prioritizes ...

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
