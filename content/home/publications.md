---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: collection

# This file represents a page section.
headless: true

# Activate this widget? true/false
active: true  

# Order that this section appears on the page.
weight: 2
#weight: 3 antes la deje en 90

title: Publications
subtitle: 'Articles, chapters, books, conference papers, and all these sorts of things'

content:
  # Filter on criteria
  filters:
    folders:
      - publication
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
design:
  # Choose a view for the listings: citation, list, compact
  view: citation
  columns: '1'
---

{{% callout note %}}
Easily search by [filtering publications](./publication/).
{{% /callout %}}
