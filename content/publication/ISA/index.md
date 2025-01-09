---
title: "Instance-Level Strong Augmentation for Semi-Supervised 3D Object Detection / under review at CVPR 2025"
authors:
- admin
- Yu Chen
- Nuo Chen
- Yong Du
- Huaidong Zhang
date: "2024-11-16T10:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Semi-supervised 3D object detection aims to improve model performance by leveraging both labeled and unlabeled data. Existing methods primarily focus on scene-level augmentations, such as rotation, flipping, and scaling, to enhance the training of student models. However, scene-level augmentations fail to fully exploit instance-specific information, which is essential for accurate object detection in 3D environments. In this paper, we propose ISA, Instance-level Strong Augmentation strategy, for semi-supervised 3D object detection. ISA includes three key augmentation strategies: instance switch, intra-class mixup, and inter-class mixup. These strategies enable the model to better leverage instance-specific features, improving the learning performance over unlabeled data. To ensure consistent and reliable learning, we also introduce augmentation constraints, including instance box fitting and density-controlled instance generation. These innovations work together to enhance the model’s ability to generalize across diverse scenarios. Extensive experiments on the ScanNet and SUN RGB-D datasets show that our method consistently outperforms baseline models, achieving significant improvements in detection accuracy and generalization, particularly in low-labeled data settings."

# Summary. An optional shortened abstract.
summary: Proposed an instance-level strong augmentation strategy for semi-supervised 3D object detection to fully exploit instance-specific information for accurate object detection in 3D environments.

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
