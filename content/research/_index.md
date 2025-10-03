---
title: "Research"
type: landing
sections:
  - block: collection
    content:
      title: "Working Papers"
      subtitle:
      # Pull in publication entries
      filters:
        folders: ["publication"]
        publication_types: ["working-paper"]  # show only WPs here
      count: 50
      sort_by: "date"
      sort_ascending: false
    design:
      view: card        # options: card | compact | citation
      columns: 1        # 1 = full-width items like Christina’s
  - block: collection
    content:
      title: "Publication"
      filters:
        folders: ["publication"]
        publication_types: ["article-journal"]  # published paper(s)
      count: 50
      sort_by: "date"
      sort_ascending: false
    design:
      view: card
      columns: 1