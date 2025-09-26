---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Global Optimization: A Machine Learning Approach"
authors:
  - Dimitris Bertsimas
  - admin
publication: "*Journal of Global Optimization*"
publication_types: ["2"]
date: 2025-01-01
publishDate: 2025-01-01T00:00:00Z

# Abstract and shortened version.
abstract: "Many approaches for addressing global optimization problems typically rely on relaxations of nonlinear constraints over specific mathematical primitives. This is restricting in applications with constraints that are implicit or consist of more general primitives. Trying to address such limitations, Bertsimas and Ozturk (2023) proposed OCTHaGOn as a way of solving very general global optimization problems by approximating the nonlinear constraints using hyperplane-based decision-trees and then using those trees to construct a unified MIO approximation of the original problem. We provide extensions to this approach, by (i) approximating the original problem using other MIO-representable ML models besides decision trees, such as gradient boosted trees, multi layer perceptrons and suport vector machines (ii) proposing adaptive sampling procedures for more accurate ML-based constraint approximations, (iii) utilizing robust optimization to account for the uncertainty of the sample-dependent training of the ML models, (iv) leveraging a family of relaxations to address the infeasibilities of the final MIO approximation. We then test the enhanced framework in 81 global optimization instances. We show improvements in solution feasibility and optimality in the majority of instances. We also compare against BARON, showing improved optimality gaps and solution times in more than 9 instances."

# Summary. An optional shortened abstract.
# summary: "A novel machine learning framework for global optimization that combines traditional optimization methods with modern ML algorithms to solve complex problems with black-box constraints."

# Digital Object Identifier (DOI)
doi: ""

# Is this a featured publication? (true/false)
featured: true

# Tags and categories
tags:
  - Global Optimization
  - Machine Learning
  - Mixed Integer Optimization
  - Black-box Optimization

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Journal
  url: https://link.springer.com/journal/10898
  icon_pack: fas
  icon: external-link-alt

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Global Optimization Framework'
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

<!-- ## Abstract

This paper presents a novel machine learning approach to global optimization problems. We develop a framework that leverages machine learning techniques to solve complex global optimization challenges, particularly those with black-box constraints and non-convex objectives. Our approach combines traditional optimization methods with modern machine learning algorithms to achieve superior performance on a wide range of benchmark problems.

## Key Contributions

- **Machine Learning Integration**: Novel framework combining ML with traditional optimization
- **Black-box Constraint Handling**: Effective approach for problems with implicit constraints
- **Benchmark Performance**: Superior results on standard global optimization benchmarks
- **Scalability**: Framework scales to high-dimensional optimization problems

## Journal Information

- **Journal**: Journal of Global Optimization
- **Volume**: 91, Issue 1
- **Pages**: 1-37
- **Year**: 2025 -->
