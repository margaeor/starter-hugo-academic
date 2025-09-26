---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Efficient Domain Adaptation of Multimodal Embeddings Using Contrastive Learning"
authors:
  - admin
  - Periklis Petridis
  - Dimitris J. Bertsimas
publication: "*arXiv preprint*"
publication_types: ["3"]
date: 2025-02-01
publishDate: 2025-02-01T00:00:00Z

# Abstract and shortened version.
abstract: "Recent advancements in machine learning (ML), natural language processing (NLP), and foundational models have shown promise for real-life applications in critical, albeit compute-constrainted fields like healthcare.In such areas, combining foundational models with supervised ML offers potential for automating tasks like diagnosis and treatment planning, but the limited availability of onsite computational resources pose significant challenges before applying these technologies effectively: Current approaches either yield subpar results when using pretrained models without task-specific adaptation, or require substantial computational resources for fine-tuning, which is often a barrier to entry in such environments.This renders them inaccessible in applications where performance and quality standards are high, but computational resources are scarce.To bridge the gap between best-in-class performance and accessibility, we propose a novel method for adapting foundational, multimodal embeddings to downstream tasks, without the need of expensive fine-tuning processes. Our method leverages frozen embeddings from Large Language Models (LLMs) and Vision Models, and uses contrastive learning to train a small, task-specific nonlinear projection that can be used in the downstream task, without having to fine-tune the original foundational models. We show that this efficient procedure leads to significant performance improvements across various downstream tasks, and perhaps more importantly with minimal computational overhead, offering a practical solution for the use of advanced, foundational ML models in resource-constrained settings."

# Summary. An optional shortened abstract.
# summary: "An efficient contrastive learning framework for domain adaptation of multimodal embeddings that leverages inter-modal and intra-modal relationships."

# Digital Object Identifier (DOI)
# doi: "10.48550/arXiv.2502.02048"

# Is this a featured publication? (true/false)
featured: false

# Tags and categories
tags:
  - Domain Adaptation
  - Multimodal Learning
  - Contrastive Learning
  - Embeddings
  - Transfer Learning

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: arXiv
  url: https://arxiv.org/abs/2502.02048
  icon_pack: ai
  icon: arxiv
# - name: PDF
#   url: https://arxiv.org/pdf/2502.02048.pdf
#   icon_pack: fas
#   icon: file-pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Multimodal Domain Adaptation Framework'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
<!-- 
## Abstract

We present an efficient approach for domain adaptation of multimodal embeddings using contrastive learning. Our method addresses the challenge of adapting pre-trained multimodal models to new domains while maintaining their performance on downstream tasks. We introduce a novel contrastive learning framework that leverages both inter-modal and intra-modal relationships to improve adaptation efficiency and effectiveness. Experimental results demonstrate significant improvements in adaptation speed and performance across various multimodal tasks.

## Key Contributions

- **Efficient Adaptation**: Novel framework for fast and effective domain adaptation
- **Contrastive Learning**: Leverages both inter-modal and intra-modal relationships
- **Multimodal Focus**: Specifically designed for multimodal embedding adaptation
- **Performance Gains**: Significant improvements in adaptation speed and effectiveness

## Publication Information

- **Type**: arXiv preprint
- **Identifier**: arXiv:2502.02048
- **Year**: 2025
- **Citations**: 1 -->
