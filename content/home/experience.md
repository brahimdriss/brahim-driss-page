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
  - title: Research Assistant
    company: LAMSADE, Université Paris Dauphine - PSL
    company_url: ''
    location: Paris
    date_start: '2022-04-01'
    date_end: ''
    description: Modification and scaling of AlphaZero in the game of Go, with multiplayer adaptation.
    
  - title: Research Assistant
    company: LAMSADE, Université Paris Dauphine - PSL
    company_url: ''
    location: Paris
    date_start: '2021-04-01'
    date_end: '2021-09-01'
    description: |2-
      * Deep Reinforcement Learning and Monte Carlo Tree Search on Settlers Of Catan game
      * Implemented and adapted of Expert Iteration, a similar approach to DeepMind’s AlphaGo Zero.

  - title: Data Science Internship,
    company: Wevioo
    company_url: ''
    location: Tunis
    date_start: '2020-07-01'
    date_end: '2020-09-31'
    description: |2-
    * Searched and implemented a State of the art Deep Learning approach for Time Series forecasting
    * Handled other exogenous variables that have an impact on the evolution of the temporal data, 
    * Reduced by 2% the mean absolute error compared to previously used methods.
    * Deployed final solution as a REST API using Flask.
   
   - title: Software developer Internship,
      company: BH Bank
      company_url: ''
      location: Tunis
      date_start: '2020-07-01'
      date_end: '2020-09-31'
      description: Development of a Workflow automation web application, handling expense requests.


design:
  columns: '2'
---
