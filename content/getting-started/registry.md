+++
widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

title = "Install the BioJulia registry"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  #gradient_start = "DarkGreen"
  #gradient_end = "ForestGreen"
  
  #Background image.
  #image = "image.jpg"  # Name of image in `static/img/`.
  #image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

Julia by default only watches the "General" package registry, so before you
start, you should add the BioJulia package registry.

Start a julia terminal, hit the `]` key to enter pkg mode (you should see the
prompt change from `julia> ` to `pkg> `), then enter the following command:

```julia
registry add https://github.com/BioJulia/BioJuliaRegistry.git
```

Then hit enter.

After you've added the registry, you can install BioJulia packages from the
julia REPL. Press `]` to enter pkg mode again, and enter the following:

```julia
add pkname
```

Where `pkgname` is the name of the package you want to install.