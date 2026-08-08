---
title: 'An Improving Column Is All You Need: Enhancing Column Generation for Parallel
  Machine Scheduling via Transformers'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Amira Hijazi
- Osman Ozaltin
- Reha Uzsoy

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
publication: '*INFORMS Journal on Computing*'
publication_short: ''

doi: ''

abstract: ''

# Summary. An optional shortened abstract.
summary: >-
  This paper addresses a key computational bottleneck in column generation, namely the repeated solution of pricing subproblems. We develop a pointer transformer model (CG NN-DP) to generate new columns in each iteration of the CG for minimizing the total weighted completion time of a set of jobs on unrelated parallel machines. The proposed approach leverages a learned optimization proxy to rapidly approximate the solution of the NP-hard single-machine scheduling pricing subproblem. Computational experiments demonstrate that CG NN-DP significantly achieves faster convergence than traditional column generation with DP. We also compare CG NN-DP with a CG procedure using an efficient pricing heuristic. For medium-sized instances, both methods yield improvements of 65% to 90% over traditional CG, while CG NN-DP outperforms CG Heuristic-DP as the number of jobs increases.

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

