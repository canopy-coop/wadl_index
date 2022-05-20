+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "calc(100vh - 70px)"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "<b>Wa</b>ter <b>D</b>ata <b>L</b>ab"
  content = "Hydrologic data science and engineering"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  #overlay_color = "#666"  # An HTML color value.
  overlay_img = "delta_cir_2.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  #cta_label = "Get Academic"
  #cta_url = "https://sourcethemes.com/academic/"
  #cta_icon_pack = "fas"
  #cta_icon = "graduation-cap"

[[item]]
  # title = "Water :droplet:"
  title = "Water"
  content = "specialized consulting in water resources, remote sensing, hydrogeology, and surface and coastal hydrology"
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "patagonia.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.

[[item]]
  # title = "Data "
  title = "Data "
  content = "production grade databases, APIs, ETL pipelines, machine learning workflows, sensor networks, and dashboards"
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "shasta.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.
+++

widget: slider  # Use the Slider widget as this page section
weight: 1  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Welcome to the group
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
    - title: Lunch & Learn ☕️
      content: 'Share your knowledge with the group and explore exciting new topics together!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg
    - title: World-Class Semiconductor Lab
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
