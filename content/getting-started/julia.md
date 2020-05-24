+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 2  # Order that this section will appear.

title = "Install Julia"

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
#hero_media = "biojulia-logo-light-svgomg.svg"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = ""
  
  # Background gradient.
  # gradient_start = "#4bb4e3"
  # gradient_end = "#2b94c3"
  
  # Background image.
  #image = "bands-background.png"  # Name of image in `static/img/`.
  image = "bubble-helix-omg.png"
  image_darken = 0.7  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = true

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
[cta]
  url = "https://julialang.org"
  label = "Get Julia"
  icon_pack = "fas"
  icon = "download"
  
[cta_alt]
  url = "https://docs.julialang.org"
  label = "Julia documentation"

# Note. An optional note to show underneath the links.
#[cta_note]
#  label = '<a id="academic-release" href="https://sourcethemes.com/academic/updates" data-repo="gcushen/hugo-academic">Latest release <!-- V --></a>'
+++
