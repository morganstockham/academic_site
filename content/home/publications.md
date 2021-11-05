+++
# A Recent Publications section created with the Pages widget.
# This section displays recent blog posts from `content/publication/`.

widget = "pages"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
weight = 90  # Order that this section will appear.

title = "Working Papers"
subtitle = ""

[content]
  # Page type to display. E.g. post, talk, or publication.
  page_type = "publication"
  
  # Choose how much pages you would like to display (0 = all pages)
  count = 5
  
  # Choose how many pages you would like to offset by
  offset = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"
  
[[publication]]
  title = "District Attorney Compensation and Performance"
  abstract = """Does prosecutor pay impact performance? We attempt to identify the causal effect of wages on a prosecutor’s effort by studying a large (41%), exogenous salary increase for district attorneys in New York state. We measure the performance of prosecutors by the likelihood that a conviction is upheld when appealed. If the efficiency wage theory accurately explains non-market actor behavior, then the exogenous wage shock should entice better performance. Alternatively, if individuals who hold public office are motivated primarily by an intrinsic desire to carry out their office duties to the best of their ability rather than strictly financial compensation, then their performance would be unrelated to changes in their salary. We mostly find, inconsistent with efficiency wage theory, that an exogenous pay increase has a null effect on prosecutor performance."""

[[publication]]
  title = "Divorce and Crime in Cook County, Illinois"
  abstract = """Divorce has become a frequent part of an individual’s life cycle. Divorce impacts individuals’ lives in large and dramatic ways that affect their decision making. There exists literature that discusses why individuals marry, why they divorce, their outcomes after divorce, and how unilateral divorce laws have impacted crime at the state level. This researhc connect divorce and crime, but how does divorce causally impact a person’s likelihood to commit a crime? I utilize the random assignment of divorce judges in Cook County, Illinois, as an exogenous impact on the length of a divorce case. I find that longer divorce cases increase a person’s likelihood to commit low-level crimes when focusing on the effect of judge assignment on those tßhat file in the downtown Chicago district."""


  # Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    author = ""
    exclude_featured = false
  
[design]
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 2
  
[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
    
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

{{% alert note %}}
Quickly discover relevant content by [filtering publications]({{< ref "/publication/_index.md" >}}).
{{% /alert %}}
