---
title: 'An Improving Column Is All You Need: Enhancing Column Generation for Parallel
  Machine Scheduling via Transformers'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Amira Hijazi
- O Ozaltin
- R Uzsoy

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-05-25T16:07:40.650421Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*INFORMS Journal on Computing* (forthcoming)'
publication_short: ''

doi: ''

abstract: ''

# Summary. An optional shortened abstract.
summary: >-
  Parallel machine scheduling problems are often solved with column generation, where the slow
  step is repeatedly solving a dynamic program to find new job sequences worth adding to the plan.
  This work replaces that step with a transformer-based neural network that learns to propose good
  sequences directly, cutting computation time by 45% on small-to-medium instances while a dynamic
  program still verifies optimality. On large-scale instances, the learned approach improves
  solution quality by 80% within minutes, and the model generalizes to problem sizes and
  distributions it was never trained on.

tags: []

# Display this page in a list of Featured pages?
featured: true

# Links
url_pdf: 'https://arxiv.org/pdf/2410.15601'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
