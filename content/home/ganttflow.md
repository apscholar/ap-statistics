+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
weight = 16  # Order that this section will appear.

title = "Timeline"
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
  # color = ""
  
  # Background gradient.
  # gradient_start = ""
  # gradient_end = ""
  
  # Background image.
  # image = ""  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

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


{{<mermaid>}}
gantt
        dateFormat  YYYY-MM-DD
        axisFormat %m/%d
        title July 2019 to October 2019
        
        section Research
        Research Proposal           :done,    des1, 2019-07-01,2019-08-20
        Lit. Review                 :active,  des2, 2019-09-01, 14d
        Research Design              :         des3, after des2, 14d
        Research Methods               :         des4, after des3, 10d
        
        section Skill Development
        Indep. Study of Methods         :crit, done, 2019-07-30,30d
        Bibliography Management         :crit, done, after des1, 5d
        Data Programming                :crit, active, 30d
        LaTeX                           :crit, 7d
        Reproducible Research           :1d
        Presentation Skills             :1d
{{< /mermaid >}}


