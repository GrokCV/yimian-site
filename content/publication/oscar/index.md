---
title: "One-Stage Cascade Refinement Networks for Infrared Small Target Detection"
authors:
- admin
- Xiang Li
- Fei Zhou
- Yulei Qian
- Yaohong Chen
- Jian Yang
author_notes:
- 
- "Corresponding Author"
- 
- 
- 
- "Corresponding Author"
date: "2022-12-16T13:37:23Z"
doi: "10.1109/TGRS.2023.3243062"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Geoscience and Remote Sensing*, 61: 1-17."
publication_short: "IEEE TGRS"

abstract: Single-frame infrared small target (SIRST) detection has been a challenging task due to a lack of inherent characteristics, imprecise bounding box regression, a scarcity of real-world datasets, and sensitive localization evaluation. In this article, we propose a comprehensive solution to these challenges. First, we find that the existing anchor-free label assignment method is prone to mislabeling small targets as background, leading to their omission by detectors. To overcome this issue, we propose an all-scale pseudobox-based label assignment scheme that relaxes the constraints on the scale and decouples the spatial assignment from the size of the ground-truth target. Second, motivated by the structured prior of feature pyramids, we introduce the one-stage cascade refinement network (OSCAR), which uses the high-level head as soft proposal for the low-level refinement head. This allows OSCAR to process the same target in a cascade coarse-to-fine manner. Finally, we present a new research benchmark for infrared small target detection, consisting of the SIRST-V2 dataset of real-world, high-resolution single-frame targets, the normalized contrast evaluation metric, and the DeepInfrared toolkit for detection. We conduct extensive ablation studies to evaluate the components of OSCAR and compare its performance to state-of-the-art model- and data-driven methods on the SIRST-V2 benchmark. Our results demonstrate that a top-down cascade refinement framework can improve the accuracy of infrared small target detection without sacrificing efficiency. The DeepInfrared toolkit, dataset, and trained models are available at <https://github.com/YimianDai/open-deepinfrared>.

# Summary. An optional shortened abstract.
summary: We propose OSCAR, a one-stage cascade refinement network for single-frame infrared small target detection, along with a new benchmark consisting of the SIRST-V2 dataset, normalized contrast evaluation metric, and DeepInfrared toolkit.

tags:
- Infrared Small Target Detection
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2212.08472.pdf
url_code: 'https://github.com/YimianDai/open-deepinfrared'
url_dataset: 'https://github.com/YimianDai/open-sirst-v2'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  # focal_point: ""
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
# slides: example
---
