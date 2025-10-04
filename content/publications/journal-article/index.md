---
title: "MSBATN: Multi-Stage Boundary-Aware Transformer Network for Action Segmentation in Untrimmed Surgical Videos"
authors:
- admin
- M S Mekala
- Eyad Elyan
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-09-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: Understanding actions within surgical workflows is critical for evaluating post-operative out comes and enhancing surgical training and efficiency. Capturing and analyzing long sequences of actions in surgical settings is challenging due to the inherent variability in individual surgeon approaches, which are shaped by their expertise and preferences. This variability complicates the identification and segmentation of distinct actions with ambiguous boundary start and end points. The traditional models, such as MS-TCN, which rely on large receptive fields, that causes over-segmentation, or under-segmentation, where distinct actions are incorrectly aligned. To address these challenges, we propose the Multi-Stage Boundary-Aware Transformer Network (MSBATN) with hierarchical sliding window attention to improve action segmentation. Our approach effectively manages the complexity of varying action durations and subtle transitions by accurately identifying start and end action boundaries in untrimmed surgical videos. MSBATN introduces a novel unified loss function that optimises action classification and boundary detection as interconnected tasks. Unlike conventional binary boundary detection methods, our innovative boundary weighing mechanism leverages contextual information to precisely identify action boundaries. Extensive experiments on three challenging surgical datasets demonstrate that MSBATN achieves state-of-the-art performance, with superior F1 scores at 25% and 50%
 thresholds and competitive results across other metrics.

# Summary. An optional shortened abstract.
summary: Our proposed framework addresses these issues with hierarchical sliding window attention for global-local context and includes a novel Boundary Aware Segmentation Loss to better recognise central and boundary points.

tags:
- Source Themes
featured: false

hugoblox:
  ids:
    arxiv: 1512.04133v1

links:
  - type: pdf
    url: http://arxiv.org/pdf/1512.04133v1
  - type: code
    url: https://github.com/HugoBlox/hugo-blox-builder
  - type: dataset
    url: ""
  - type: poster
    url: ""
  - type: project
    url: ""
  - type: slides
    url: https://www.slideshare.net/
  - type: source
    url: ""
  - type: video
    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'We found that selecting the right attention module can be difficult,and neighbouring frames often lead to ambiguous results, causing over- and under-segmentation in frame-wise segmentation. '
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

> [!NOTE]
> Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
