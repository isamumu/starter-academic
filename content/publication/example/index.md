---
title: Interactive Debugging at IP Block Interfaces in FPGAs

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Marco Antonio Merlini
- Isamu Poy
- Paul Chow

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2013-07-01T00:00:00Z"
doi: "https://dl.acm.org/doi/10.1145/3431920.3439305"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-17"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Symposium of Field Programmable Gate Arrays*
publication_short: In *ISFPGA '21*

abstract: Recent developments have shown FPGAs to be effective for data centre applications, but debugging support in that environment has not evolved correspondingly. This presents an additional barrier to widespread adoption. This work proposes Debug Governors, a new open-source debugger designed for controllability and interactive debugging that can help to locate issues across multiple FPGAs.

A Debug Governor can pause, log, drop, and/or inject data into any streaming interface. These operations enable single-stepping, unit testing, and interfacing with software. Hundreds of Debug Governors can fit in a single FPGA and, because they are transparent when inactive, can be left "dormant'' in production designs.

We show how Debug Governors can be used to resolve functional problems on a real FPGA, and how they can be extended to memory-mapped protocols.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- paper1

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
