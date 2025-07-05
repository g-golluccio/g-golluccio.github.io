---
title: 'When Local Optimization is Bad: Learning What to (Not) Maximize in the Null-Space for Redundant Robot Control'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Giacomo Golluccio
  - Paolo Di Lillo
  - Alessandro Marino
  - Gianluca Antonelli

# Author notes (optional)
author_notes:
  - 'Equal contribution'

date: '2023-07-03T00:00:00Z'
doi: '10.1109/CoDIT58514.2023.10284456'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-03T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 9th IEEE International Conference on Control, Decision and Information Technologies*
publication_short: In *IEEE CODIT*

abstract: Redundancy in robot structures allows the implementation of control algorithms in which it is possible to add secondary control objectives. Those are typically functions to be minimized/maximized and projected onto the null-space of the primary control objectives. As an example, typical metrics to maximize are the robot manipulability or the distance from its mechanical joint limits. Usually, designer's heuristics is used to decide which function eventually to optimize. This paper shows that heuristics may lead to counter-intuitive results such as, for example, reducing the dexterous workspace with respect to, e.g., avoiding optimization at all. A learning algorithm is proposed to allow the robot to dynamically select the function to optimize in a way to increase the overall dexterous workspace with respect to the static, heuristic choice. As a result, the robot will be able to increase its dexterous workspace by selecting the proper lower-priority task via the use of a neural network trained during a proper supervised learning process. A 3-link planar manipulator is used as numerical case study.

# Summary. An optional shortened abstract.
summary: 

tags:
  - 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10284456'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---