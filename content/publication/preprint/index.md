---
title: "Contextual Stochastic Optimization for Omnichannel Multi-Courier Order Fulfillment Under Delivery Time Uncertainty"
authors: 
- Tinghan Ye, Sikai Cheng, admin, Pascal Van Hentenryck
date: "2024"
doi: "
https://doi.org/10.48550/arXiv.2409.06918"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ["article"]

# Publication name and optional abbreviated publication name.
# publication: ""
# publication_short: ""

abstract: The paper studies a large-scale order fulfillment problem for a leading e-commerce company in the United States. The challenge involves selecting fulfillment centers and shipping carriers with observational data only to efficiently process orders from a vast network of physical stores and warehouses. The company's current practice relies on heuristic rules that choose the cheapest fulfillment and shipping options for each unit, without considering opportunities for batching items or the reliability of carriers in meeting expected delivery dates. The paper develops a data-driven Contextual Stochastic Optimization (CSO) framework that integrates distributional forecasts of delivery time deviations with stochastic and robust order fulfillment optimization models. The framework optimizes the selection of fulfillment centers and carriers, accounting for item consolidation and delivery time uncertainty. Validated on a real-world data set containing tens of thousands of products, each with hundreds of fulfillment options, the proposed CSO framework significantly enhances the accuracy of meeting customer-expected delivery dates compared to current practices. It provides a flexible balance between reducing fulfillment costs and managing delivery time deviation risks, emphasizing the importance of contextual information and distributional forecasts in order fulfillment. This is the first paper that studies the omnichannel multi-courier order fulfillment problem with delivery time uncertainty through the lens of contextual optimization, fusing machine learning and optimization.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: false

# links:
# - name: Custom Link
 # url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  # focal_point: ""
 #  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
