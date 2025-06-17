---
title: "Deep Learning-based Collision Detection Framework for Robot Tasks in Clutter"
authors:
- Giacomo Golluccio
- Daniele Di Vito
- Gianluca Antonelli
- Alessandro Marino
author_notes:
- "Equal contribution"
date: "2025-05-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Robotica"
publication_short: ""

abstract: In this work, the problem of reliably checking collisions between robot manipulators and the surrounding environment in short time for tasks, such as replanning and object grasping in clutter, is addressed. Geometric approaches are usually applied in this context; however, they can result not suitable in highly time-constrained applications. The purpose of this paper is to present a learning-based method able to outperform geometric approaches in clutter. The proposed approach uses a neural network (NN) to detect collisions online by performing a classification task on the input represented by the depth image or point cloud containing the robot gripper projected into the application scene. Specifically, several state-of-the-art NN architectures are considered, along with some customization to tackle the problem at hand. These approaches are compared to identify the model that achieves the highest accuracy while containing the computational burden. The analysis shows the feasibility of the robot collision checker based on a deep learning approach. In fact, such approach presents a low collision detection time, of the order of milliseconds on the selected hardware, with acceptable accuracy. Furthermore, the computational burden is compared with state-of-the-art geometric techniques. The entire work is based on an industrial case study involving a KUKA Agilus industrial robot manipulator at the Technology & Innovation Center of KUKA Deutschland GmbH, Germany. Further validation is performed with the Amazon Robotic Manipulation Benchmark (ARMBench) dataset as well, in order to corroborate the reported findings

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.cambridge.org/core/journals/robotica/article/abs/deep-learningbased-collision-detection-framework-for-robot-tasks-in-clutter/FE07A6D9E4E35A0116A76AEB26C6E6F0
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
