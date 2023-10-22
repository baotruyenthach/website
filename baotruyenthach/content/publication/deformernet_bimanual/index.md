---
title: 'DeformerNet: Learning Bimanual Manipulation of 3D Deformable Objects'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bao Thach
  - Tucker Hermans
  - Alan Kuntz

# Author notes (optional)
author_notes:
  - 'Utah, PhD student'
  - 'NVIDIA, PhD advisor'
  - 'Utah, PhD advisor'

date: '2023-10-31T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In IEEE Transactions on Robotics (T-RO), 2023
publication_short: In IEEE Transactions on Robotics (T-RO), 2023

abstract: Applications in fields ranging from home care to warehouse fulfillment to surgical assistance require robots to reliably manipulate the shape of 3D deformable objects. Analytic models of elastic, 3D deformable objects require numerous parameters to describe the potentially infinite degrees of freedom present in determining the object's shape. Previous attempts at performing 3D shape control rely on hand-crafted features to represent the object shape and require training of object-specific control models. We overcome these issues through the use of our novel DeformerNet neural network architecture, which operates on a partial-view point cloud of the manipulated object and a point cloud of the goal shape to learn a low-dimensional representation of the object shape. This shape embedding enables the robot to learn a visual servo controller that computes the desired robot end-effector action to iteratively deform the object toward the target shape. We demonstrate both in simulation and on a physical robot that DeformerNet reliably generalizes to object shapes and material stiffness not seen during training. Crucially, using DeformerNet, the robot successfully accomplishes three surgical sub-tasks:retraction (moving tissue aside to access a site underneath it), tissue wrapping (a sub-task in procedures like aortic stent placements), and connecting two tubular pieces of tissue (a sub-task in anastomosis).

# Summary. An optional shortened abstract.
summary: We pioneer a novel machine learning pipeline for robotic manipulation of deformable objects in surgery and warehouses, by developing a novel neural network that predicts robot actions based on point cloud observation. My work outperforms the previous learning-based method by 240% in terms of Chamfer distance.

# tags: []
tags:
  - for_portfolio

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Project Website
  url: https://sites.google.com/view/deformernet-journal/
- name: Video
  url: https://youtu.be/esBdUBWDDro
- name: Paper PDF
  url: https://arxiv.org/abs/2305.04449  
- name: "Category: Machine Learning, Robotics"
  url: none

# url_project: 'https://sites.google.com/view/deformernet-journal/'
# url_code: 'https://arxiv.org/abs/2305.04449'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtu.be/esBdUBWDDro'
# url_pdf: 'https://arxiv.org/abs/2305.04449'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: Bottom
  preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
#   - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example

---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
