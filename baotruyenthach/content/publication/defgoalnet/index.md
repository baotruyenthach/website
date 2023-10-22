---
title: 'DefGoalNet: Contextual Goal Learning from Demonstrations For Deformable Object Manipulation'

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
publication_types: ['paper-conference']
# publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In IEEE International Conference on Robotics and Automation (ICRA), 2024
publication_short: In IEEE International Conference on Robotics and Automation (ICRA), 2024

abstract: Shape servoing, a robotic task dedicated to controlling objects to desired goal shapes, is a promising approach to deformable object manipulation. An issue arises, however, with the reliance on the specification of a goal shape. This goal has been obtained either by a laborious domain knowledge engineering process or by manually manipulating the object into the desired shape and capturing the goal shape at that specific moment, both of which are impractical in various robotic applications. In this paper, we solve this problem by developing a novel neural network DefGoalNet, which learns deformable object goal shapes directly from a small number of human demonstrations. We demonstrate our method's effectiveness on various robotic tasks, both in simulation and on a physical robot. Notably, in the surgical retraction task, even when trained with as few as 10 demonstrations, our method achieves a median success percentage of nearly 90%. These results mark a substantial advancement in enabling shape servoing methods to bring deformable object manipulation closer to practical, real-world applications.

# Summary. An optional shortened abstract.
summary: We initiate the first method for solving the impractical goal specification problem in robotic deformable object shape servoing, by architecting a neural network that predicts the object's goal shapes using human demonstrations.

# tags: []
tags:
  - for_portfolio

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Project Website
  url: https://sites.google.com/view/defgoalnet/
- name: Video
  url: https://youtu.be/OIPPZKD9JLE
- name: Paper PDF
  url: https://arxiv.org/abs/2309.14463  
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
