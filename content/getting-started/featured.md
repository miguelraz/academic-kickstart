+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

title = "Explore packages and projects"
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
  
  # Background image.
  image = "bubble-helix-omg.png"  # Name of image in `static/img/`.
  image_darken = 0.7  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  image_position = "center"  # Options include `left`, `center` (default), or `right`.
  image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

Once you have julia installed you're ready to start using packages!

To see all the packages BioJulia offers you can look at the listing on JuliaHub
[here](https://juliahub.com/ui/Packages?q=BioJulia) or click the "Software Packages"
item in the menu-bar at the top of this page.

Once there, you can also filter by tags e.g. "FASTA", or "DNA", or "Alignment", or "sam-format".

Once you have decided the packages you want to use for your project, change to the
directory of your project, and start a julia session, and enter "Pkg mode" by
hitting the ']' key. Then type in `activate .` and hit enter - you should see
the cursor change to display the name of the project/folder.
Once the project is activated, you can add packages by typing `add` followed by
the package name, and hit enter.

The asciicast below shows what this process looks like for creating a project
"my_project", that uses the packages BioSequences and FASTX.

Whenever you run julia from inside a project always remember to `activate` or
start julia with the `--project` flag.

[![asciicast](https://asciinema.org/a/333487.svg)](https://asciinema.org/a/333487)