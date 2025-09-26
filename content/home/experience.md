---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: 'Graduate Researcher – Advisor: Prof. D. Bertsimas'
    company: Massachusetts Institute of Technology
    company_url: 'https://web.mit.edu/'
    company_logo: org-mit
    location: Cambridge, MA
    date_start: '2021-09-01'
    date_end: ''
    description: |2-
        **Research Projects:**
        * Develop RAG-based system that significantly improves diagnostic accuracy and explainability of healthcare pipelines ([Preprint](https://arxiv.org/abs/2507.00205), revision in *Nature Digital Medicine (npj)*)

        * Large Language Models for diagnosing **100s** of healthcare conditions from the patient's Electronic Health Record (ongoing work).

        * Efficiently adapting multimodal Vision & LLM embeddings into a downstream task for significant perfromance improvements ([Preprint](https://arxiv.org/pdf/2502.02048))

        * Large Language Models to formulate and solve Robust Optimization Problems ([Preprint](https://arxiv.org/abs/2501.00568))

        * Solving Global Optimization Problems using Machine Learning ([*Journal of Global Optimization*](https://link.springer.com/article/10.1007/s10898-024-01434-9))

  - title: ML Intern – Google Cloud AI
    company: Google
    company_url: 'https://cloud.google.com/'
    company_logo: org-google
    location: Sunnyvale, CA
    date_start: '2025-06-01'
    date_end: '2025-08-31'
    description: |2-
      * Implemented and trained 8+ recommendation models using state-of-the-art LLMs. 
      * Compared LLM-based recommenders against traditional models and production systems. 
      * Implemented methods that improved cold-start recommendation performance by **10+**%.
  - title: ML Research Engineer Intern – Recommendation Algorithms
    company: Netflix
    company_url: 'https://netflix.com/'
    company_logo: org-netflix
    location: Los Gatos, CA
    date_start: '2024-05-01'
    date_end: '2024-08-31'
    description: |2-
      * Worked on improving Netflix's core recommendation algorithm. 
      * Implemented a multimodal recommendation pipeline using state-of-the-art LLMs, Vision Transformers and Contrastive Learning. 
      * Scaled the pipeline to production-size data and showed **3-5%** improvement in recommendation quality.

  - title: Co-Founder & AI Software Engineer
    company: Guestflip
    company_url: ''
    company_logo: org-gf
    location: Athens, Greece
    date_start: '2017-12-01'
    date_end: '2019-02-01'
    description: |2-
        *	Developed an NLP system that analyzes hotel reviews, detects polarity, and identifies guests’ complaints.
        *	The system suggests responses to the review depending on the sentiment and the type of complaint.
        *	Full-stack web development of the company’s web platform in Laravel-PHP.


  - title: Research Intern
    company: Foundation of Research and Technology Hellas (FORTH)
    company_url: ''
    company_logo: org-forth
    location: Heraklion, Greece
    date_start: '2019-07-01'
    date_end: '2019-09-25'
    description: |2-
      Worked on a project called "Human Behavioral Profiling" in the Computer Vision and Robotics Laboratory. Our goal was to utilize dynamic models and reinforcement learning in order to make a robotic arm imitate tasks performed by a human.
      
      Responsibilities included:
        
        * Develop dynamic models in C++ and Python
        * Adapt these models to use Reinforcement Learning
        * Interact with ROS to control a robotic arm

design:
  columns: '2'
---