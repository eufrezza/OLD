---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
 
  - block: about.avatar
    id: about
    folders:
      - home 
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: I am a PhD candidate in Economics at Trinity College Dublin and I am an Irish Research Council scholar. My main research interests revolve around social Norms, intimate partner violence, and education in developing countries.

      
       
    
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      #default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      #buttons:
       # - name: All
        #  tag: '*'
        #- name: Deep Learning
        #  tag: Deep Learning
        #- name: Other
        #  tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  
  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      columns: '2'
      view: compact

---
