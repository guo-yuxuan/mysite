---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing


sections:
  - block: about.biography
    id: about
    content:
      title: Welcome!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: projects
    content:
      title: Projects 
      filters:
        folders:
          - project
        featured_only: true
      archive:
        enable: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false 
      

---
