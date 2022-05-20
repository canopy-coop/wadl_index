---
title: Remote Sensing-based Water Balance
summary: Automated remote-sensing based software framework to assess groundwater changes
#tags: 
#  - Remote Sensing
#  - Water Resources
#  - Data Science
date: "2022-02-28T00:00:00Z"
share: true

# Optional external URL for project (replaces project detail page).
#external_link: 

#header:
#  image: "SLIP.jpg"
#  caption: "Image credit: [**Aakash Ahamed**](https://www.kashingtondc.github.io)"

image: 
  caption: 
  focal_point: Smart
  preview_only: false

links:
- name: Paper
  url: https://doi.org/10.1016/j.scitotenv.2021.150635
- icon: github
  icon_pack: fab
  name: Github
  url: https://github.com/kashingtonDC/RS_GW


url_project: 
#url_pdf: ""
#url_slides: ""
#url_video: ""



# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

---

Near-real-time estimates of changes in groundwater storage are critical to effectively monitor hydrologic systems. However, few methods exist that can assess both local and regional aquifer dynamics, especially in regions where groundwater monitoring wells are sparse or data is not publicly available. We developed a method that uses a combination of satellite and ground-based measurements of hydrologic properties (e.g., rainfall and soil moisture) to calculate changes in groundwater storage, and demonstrated this method in California’s Central Valley.

{{< figure src="cvws_swe.gif" title="UC Boulder Snow-Water-Equivalent" lightbox="true" >}}

 Our results agree with gravity measurements, physics-based flow models, and groundwater storage changes calculated from water levels in wells. The correspondence in trend, magnitude, and timing of storage changes confirmed by independent datasets improves our certainty in the amount of groundwater depletion in California occurring over the last ~20 years. Our approach relies heavily on remotely-sensed data; thus it may be readily extensible to other semiarid regions worldwide, and areas with limited access to data.
