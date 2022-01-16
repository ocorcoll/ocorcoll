---
title: "Disentangling causal effects for hierarchical reinforcement learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Raul Vicente

# Author notes (optional)
author_notes:
- "Corresponding"
# - "Equal contribution"

date: "2022-01-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Conference on Causal Learning and Reasoning (CLeaR)
# publication_short: Causal Learning and Reasoning (CLeaR)


abstract: Exploration and credit assignment under sparse rewards are still challenging problems. We argue that these challenges arise in part due to the intrinsic rigidity of operating at the level of actions. Actions can precisely define how to perform an activity but are ill-suited to describe what activity to perform. Instead, causal effects are inherently composable and temporally abstract, making them ideal for descriptive tasks. By leveraging a hierarchy of causal effects, this study aims to expedite the learning of task-specific behavior and aid exploration. Borrowing counterfactual and normality measures from causal literature, we disentangle controllable effects from effects caused by other dynamics of the environment. We propose CEHRL, a hierarchical method that models the distribution of controllable effects using a Variational Autoencoder. This distribution is used by a high-level policy to 1) explore the environment via random effect exploration so that novel effects are continuously discovered and learned, and to 2) learn task-specific behavior by prioritizing the effects that maximize a given reward function. In comparison to exploring with random actions, experimental results show that random effect exploration is a more efficient mechanism and that by assigning credit to few effects rather than many actions, CEHRL learns tasks more rapidly.


# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Arxiv
  url: https://arxiv.org/abs/2010.01351

url_pdf: 'publication/cehrl/paper.pdf'
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
slides: ""
---