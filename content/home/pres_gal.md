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
  image = "images/gilles.webp"
  caption = "caption"

[[gallery_item]]
  album = "gallery"
  image = "images/computer.webp"
  caption = "caption"

[[gallery_item]]
  album = "gallery"
  image = "images/piano.webp"
  caption = "caption"
+++
<div class="container-fluid">
    <div id="carouselExample" class="carousel slide" data-ride="carousel" data-interval="9000">
        <div class="carousel-inner row w-10 mxauto" role="listbox">
            <div class="carousel-item col-md-4 active">
                <img class="img-fluid mx-auto d-bloc" src="media/images/computer.webp" alt="slide 1">
            </div>
            <div class="carousel-item col-md-4">
                <img class="img-fluid mx-auto d-block" src="media/images/piano.webp" alt="slide 2">
            </div>
            <div class="carousel-item col-md-4">
                <img class="img-fluid mx-auto d-block" src="media/images/gilles.webp" alt="slide 3">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExample" role="button" data-slide="prev">
            <i class="fa fa-chevron-left fa-lg text-muted"></i>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next text-faded" href="#carouselExample" role="button" data-slide="next">
            <i class="fa fa-chevron-right fa-lg text-muted"></i>
            <span class="sr-only">Next</span>
        </a>
    </div>
</div>
