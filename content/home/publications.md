---
# An instance of the Featured widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 80

title: Publications
subtitle: "A selection of my publications"

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publications
  # Choose how many pages you would like to display (0 = all pages)
  count: 5
  # Filter on criteria
  filters:
    author: ""
    category: ""
    publication_type: ""
    tag: ""
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

design:
design:
  background:
    # Name of image in `assets/media/`.
    image: splash.jpg
    # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
    image_darken: 0.6
    #  Options are `cover` (default), `contain`, or `actual` size.
    image_size: cover
    # Options include `left`, `center` (default), or `right`.
    image_position: center
    # Use a fun parallax-like fixed background effect on desktop? true/false
    image_parallax: true
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true

  view: 1
---
