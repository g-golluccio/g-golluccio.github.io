---
title: "Objects Relocation in Clutter with Robot Manipulators via Tree-based Q-Learning Algorithm"
authors:
- Giacomo Golluccio
- Paolo Di Lillo
- Daniele Di Vito
- Alessandro Marino
- Gianluca Antonelli
author_notes:
- "Equal contribution"
date: "2022-10-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Intelligent & Robotic Systems"
publication_short: "JINT"

abstract: This work addresses the problem of retrieving a target object from cluttered environment using a robot manipulator. In the details, the proposed solution relies on a Task and Motion Planning approach based on a two-level architecture - the high-level is a Task Planner aimed at finding the optimal objects sequence to relocate, according to a metric based on the objects weight; the low-level is a Motion Planner in charge of planning the end-effector path for reaching the specific objects taking into account the robot physical constraints. The high-level task planner is a Reinforcement Learning agent, trained using the information coming from the low-level Motion Planner. In this work we consider the Q-Tree algorithm, which is based on a dynamic tree structure inspired by the Q-learning technique. Three different RL-policies with two kinds of tree exploration techniques (Breadth and Depth) are compared in simulation scenarios with different complexity. Moreover, the proposed learning methods are experimentally validated in a real scenario by adopting a KINOVA Jaco 7-DoFs robot manipulator.

# Summary. An optional shortened abstract.
summary: 

tags: Motion Planning - Task Planning - Reinforcement Learning
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/article/10.1007/s10846-022-01719-9
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 
url_video: https://www.youtube.com/watch?v=2aTqmWzmiJ8

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
