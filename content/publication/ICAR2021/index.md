---
title: 'Robotic Weight-based Object Relocation in Clutter via Tree-based Q-learning Approach using Breadth and Depth Search Techniques'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Giacomo Golluccio
  - Daniele Di Vito
  - Alessandro Marino
  - Gianluca Antonelli

# Author notes (optional)
author_notes:
  - 'Equal contribution'

date: '2021-12-06T00:00:00Z'
doi: '10.1109/CoDIT58514.2023.10284456'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-12-06T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2021 20th IEEE International Conference on Advanced Robotics*
publication_short: In *IEEE ICAR*

abstract: In this paper, the problem of retrieving a target object from a cluttered environment through a mobile manipulator is considered. The task is solved by combining Task and Motion Planning; in detail, at a higher level, the task planner is in charge of planning the sequence of objects to relocate while, at a lower level, the motion planner is in charge of planning the robot movements taking into consideration robot and environment constraints. In particular, the latter provides feedback to the former about the feasibility of object sequences; this information is exploited to train a Reinforcement Learning agent that, according to an objects-weight based metrics, builds a dynamic decision-tree where each node represents a sequence of relocated objects, and edge values are weights updated via Q-learning-inspired algorithm. Three learning strategies differing in how the tree is explored are analysed. Moreover, each exploration approach is performed using two different tree-search methods - the Breadth first and Depth first techniques. Finally, the proposed learning strategies are numerically validated and compared in three scenarios of growing-complexity.

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

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9659471'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=6z7Cppao-gM'

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