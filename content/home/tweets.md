+++
# A Tweet Gallery section created with the Portfolio widget.
# This section displays selected tweets from `content/tweet/`.

widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 70  # Order that this section will appear.

title = "Tweet Gallery"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "tweet"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 4
  
  [[content.filter_button]]
    name = "All"
    tag = "*"

  [[content.filter_button]]
    name = "2021"
    tag = "2021"

  [[content.filter_button]]
    name = "2020"
    tag = "2020"
    
  [[content.filter_button]]
    name = "2019"
    tag = "2019"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

+++