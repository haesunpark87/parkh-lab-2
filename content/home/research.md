---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: 'Research Ares'
subtitle: 'We aims to tackle the challenges related to energy problems.'

content:
  # Page type to display. E.g. project.
  page_type: research
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Advanced Li-ion 
      tag: ALB
    - name: Multivalent Batteries
      tag: MV
    - name: Data-driven Discovery Materials
      tag: NVL
  design:
    # Choose how many columns the section has. Valid values: '1' or '2'.
    columns: '2'
    # Choose a listing view
    view: 2
    # For Showcase view, flip alternate rows?
    flip_alt_rows: false
design:
  columns: '2'
  view: masonry
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---