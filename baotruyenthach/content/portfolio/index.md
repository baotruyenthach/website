---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing


sections:
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'


 
  - block: collection
    id: featured
    content:
      title: Machine Learning / Robotics
      subtitle: Featured Projects
      filters:
        folders:
          - publication
        featured_only: false
        # tag: for_portfolio
    design:
      columns: '2'
      view: card
 
---
