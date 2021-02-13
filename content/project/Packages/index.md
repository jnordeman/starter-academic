---
title: "Package Dev"
summary:  Developed internal R-packages that faciliates data retrieval, data wrangling and data visualisation 
tags:
- Other
date: "2021-01-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""


links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

image:
  caption: Artwork by @allison_horst
  focal_point: Smart

---

At the ECB I had the opportunity to develop and contribute to various internal R-packages. I learned that unlike open-source packages,  internal packages can embrace institutional knowledge in two important ways. First, they have the possibility to solve domain-specific issues. Second, they allow for more holistic solutions by internalising the full breadth of the necessary work-flows. In this case, the work-flow consisted of three steps (i) data retrieval, (ii) data wrangling and (iii) data visualisation.

The package related to data retrieval, houses a number of functions to take data from the different sources. The functions are designed to give similar input options and outputs where possible no matter the source.

The package for data wrangling aims at solving one specific issue: calculating the contribution of components to the annual growth rate of the HICP. In other words, it enables decomposing the growth rate of a series in a fully additive manner.  The function provides precise values not only in the case of fixed-based Laspeyres-index series, but also for chain-indexed series with changing sub-component weights.

The package for data visualisation facilitates making data visualisation at large scale within the ECB. It is built using ggplot2 but tailored for visualising economic time series data.  The package also seeks to minimize not only the initial threshold that naturally occur for those learning a new software language but also the fine-tuning required when reusing a chart for a different purpose (e.g. using the chart in both external publication and internal presentation).
