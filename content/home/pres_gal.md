+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 17  # Order that this section will appear.

#title = "## Bienvenu au Studiodé"
#subtitle = "### Un studio 100% Libre"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  color = "white"
  
  # Background gradient.
  #gradient_start = "#"
  #gradient_end = "#000000"
  
  
  # Text color (true=light or false=dark).
  #text_color_light = false


[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
 
[[gallery_item]]
  album = "gallery"
  image = "images/tn.png"
  caption = "caption"

[[gallery_item]]
  album = "gallery"
  image = "images/20201130_0006_01.webp"
  caption = "caption"

[[gallery_item]]
  album = "gallery"
  image = "images/tn.png"
  caption = "caption"
+++

{{<gallery album="gallery">}}
