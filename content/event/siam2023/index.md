---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Global Optimization Using Maching Learning"
event:
event_url:
location: "SIAM Conference on Optimization (OPT23)"
address:
  street:
  city: Seattle
  region:
  postcode: Washington
  country: U.S.
summary:
abstract: "Many approaches for addressing Global Optimization problems typically rely on relaxations of nonlinear constraints over specific mathematical primitives. This is restricting in applications with constraints that are black-box, implicit or consist of more general primitives. Trying to address such limitations, Bertsimas and Ozturk (2022) proposed OCTHaGOn as a way of solving black-box global optimization problems by approximating the nonlinear constraints using hyperplane-based Decision-Trees and then using those trees to construct a unified MIO approximation of the original problem. We provide significant extensions to this approach, by (i) approximating the original problem using a much richer family of MIO-representable ML models besides Decision Trees, (ii) proposing adaptive sampling procedures for more accurate ML-based constraint approximations, (iii) utilizing robust optimization to account for the uncertainty of the sample-dependent training of the ML models and (iv) leveraging a family of relaxations to address the infeasibilities of the final MIO approximation. We show the improvements resulting from those enhancements through a wide range of Global Optimization benchmarks. We demonstrate the promise of the enhanced approach in finding globally optimal solutions, and compare it with well-established global optimizers such as BARON."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2023-05-29
#date_end: 2023-03-06T02:03:37-05:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2023-03-06T02:03:37-05:00

authors: [Dimitris Bertsimas, George Margaritis]
tags: [Global Optimization, Machine Learning, Mixed Integer Optimization]

# Is this a featured event? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your event's folder or a URL.
url_slides: uploads/goml.pdf

url_code:
url_pdf: https://link.springer.com/article/10.1007/s10898-024-01434-9
url_video:

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---