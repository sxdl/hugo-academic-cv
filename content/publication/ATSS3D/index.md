---
title: "ATSS3D: Adaptive Threshold for Semi-Supervised 3D Object Detection / under review"
authors:
- Chen Yu
- admin
- Chen Nuo
- Du Yong
- Zhang Huaidong
date: "2024-11-16T10:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T10:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Semi-supervised 3D object detection leverages unlabeled data which effectively solve the challenge of substantial time and energy costs required for labeling large-scale datasets. Existing pseudo-labeling based method generate high-quality pseudo labels for unlabeled data through a teacher network, and use a student network for joint training to improve detection performance and generalization ability. In this process, a threshold is manually set to a fixed value to filter generated pseudo labels, in order to prevent the inclusion of a large number of low-quality and erroneous predictions to the training set. However, fixed thresholds are hardly adaptable to the characteristics of different categories and scenarios, which may lead to uneven quality of pseudo labels. To address this issue, we propose ATSS3D, a probabilistic decision adaptive threshold for semi-supervised 3D object detection method based on learned states. Specifically, ATSS3D introduces a scene-level adaptive threshold to flexibly handle unlabeled data utilization based on the class frequencies of current scene. Additionally, we introduce a batch-level probability weighting mechanism to estimate confidence distributions for each class, enabling adaptive threshold filtering according to the model's performance on the current batch. Finally, we dynamically adjusts the thresholds using class prediction scores, enabling the adaptive threshold function to better reflect the class distribution characteristics in each training step. Our experiments on the ScanNet and SUN RGB-D benchmark datasets show that ATSS3D significantly improves the performance of current semi-supervised 3D object detection methods, especially with small amounts of labeled data."

# Summary. An optional shortened abstract.
summary: Proposed a probabilistic decision adaptive thresholding method for semi-supervised 3D object detection, which dynamically adjusts thresholds based on learned states at scene, batch, and class levels, effectively improving pseudo-label quality and detection performance on ScanNet and SUN RGB-D.

tags:
- Semi-supervised Learning
- 3D Object Detection

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 
url_code: 
url_dataset: 
url_poster: 
url_project: 
url_slides: 
url_source: 
url_video: 

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
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
# slides: example
---
<!-- 
This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
