---
title: 'Accounting for Hysteresis in the Forward Kinematics of Nonlinearly-Routed Tendon-Driven Continuum Robots via a Learned Deep Decoder Network'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:  
  - Brian Cho
  - Bao Thach
  - Alan Kuntz

# Author notes (optional)
author_notes:
  - 'Utah, PhD student'
  - 'Utah, PhD student'
  - 'Utah, PhD advisor'

date: '2023-03-31T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In IEEE Robotics and Automation Letters (RA-L), 2023
publication_short: In IEEE Robotics and Automation Letters (RA-L), 2023

abstract: Tendon-driven continuum robots have been gain- ing popularity in medical applications due to their ability to curve around complex anatomical structures, potentially reduc- ing the invasiveness of surgery. However, accurate modeling is required to plan and control the movements of these flexible robots. Physics-based models have limitations due to unmodeled effects, leading to mismatches between model prediction and actual robot shape. Recently proposed learning-based methods have been shown to overcome some of these limitations but do not account for hysteresis, a significant source of error for these robots. To overcome these challenges, we propose a novel deep decoder neural network that predicts the complete shape of tendon-driven robots using point clouds as the shape representation, conditioned on prior configurations to account for hysteresis. We evaluate our method on a physical tendon- driven robot and show that our network model accurately predicts the robot’s shape, significantly outperforming a state- of-the-art physics-based model and a learning-based model that does not account for hysteresis.

# Summary. An optional shortened abstract.
summary: We engineer a state-of-the-art deep neural network capable of predicting the complete shape of tendon-driven surgical robots, outperforming the previous physics-based model by 26.5 times in terms of proximity to the ground truth shape.

# tags: []
tags:
  - for_portfolio

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Project Website
  url: https://sites.google.com/view/tendonnet/
# - name: Video
#   url: https://youtu.be/OIPPZKD9JLE
# - name: Paper PDF
#   url: https://arxiv.org/abs/2309.14463  
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
