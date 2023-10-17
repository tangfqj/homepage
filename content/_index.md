---
# Leave the homepage title empty to use the site title
title: Qijun Feng
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publication
        # exclude_featured: true
    design:
      columns: '2'
      view: citation
 
---
