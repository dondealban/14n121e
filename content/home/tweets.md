+++
# A Tweet Gallery section created with the Portfolio widget.
# This section displays selected tweets from `content/tweet/`.

widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 70  # Order that this section will appear.

title = "Tweet Gallery"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "tweet"

  # Choose how much pages you would like to display (0 = all pages)
  count = 3
  
  # Choose how many pages you would like to offset by
  offset = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

+++