---
title: "Research"
type: landing
sections:
  - block: collection
    content:
      title: "Working Papers"
      count: 50
      filters:
        folders: ["publication"]       # pull from the Publications section
        publication_type: "working-paper"
      sort_by: "Date"
      sort_ascending: false
    design:
      view: card
      columns: 1

  - block: collection
    content:
      title: "Publication"
      count: 50
      filters:
        folders: ["publication"]
        publication_type: "article-journal"
      sort_by: "Date"
      sort_ascending: false
    design:
      view: card
      columns: 1
---
