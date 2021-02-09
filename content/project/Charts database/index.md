---
title: "Economics Dashboard"
summary: Analytical tool used to visualise the latest economic developments 
tags:
- Other
date: "2020-08-15T00:00:00Z"

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
---

During my traineeship at the ECB, I authored a pipeline to create a common data platform that spans across divisions and provides up-to-date visualisations. The dashboard is now widely used by ECB staff and members of the Executive Board and thematically organises data and charts required for the Governing Council meetings and external communications (e.g. Economic Bulletin and speeches). 

The project was part of the Directorate General Economics’ strategy for more modern data management and was carried out in three steps. First, a colleague and I wrote R packages that facilitate making (i) data retrieval and (ii) data visualisation at a large scale for colleagues at the bank. These packages also aim to minimize the initial threshold that naturally occurs for those learning a new software language. Next, we created an infrastructure that enables data delivery at scale without compromising the user experience. During this process, I learned not only how to make some basic web development (e.g. customise the aesthetics of the dashboard using HTML and CSS) but also how to ensure reproducibility and reliability (e.g. testing and version control). Finally, we migrated existing processes to the new pipeline. For the most part, this step entailed supporting colleagues in the migration and providing various exercise sessions aimed to give a basic grounding in the use of modern data and programming tools. 
