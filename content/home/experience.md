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
  - title: Senior Quantitative Analyst
    company: Smartodds Ltd
    company_url: 'https://www.smartodds.co.uk'
    company_logo: so
    location: London, UK
    date_start: '2009-09-15'
    date_end: ''
    description: |2-
        My responsibilities include:
        
        * Analysing rich event data (Opta, Wyscout, odds, ...)
        * Developing C++ libraries to fit statistical models (Large Scale Kalman Filters, Spase Matrix Library, ...)
        * Building R packages for ETL, modeling and visualization.
        * Modeling Football player ratings.
        
  - title: Graduate Lecturer in Mathematics
    company: Paris Est Sup University
    company_url: 'https://www.paris-est-sup.fr/en/'
    company_logo: Logo_Paris-Est_Sup
    location: Paris, France
    date_start: '2003-10-01'
    date_end: '2009-06-30'
    description: Taught about Algebra, Analysis, Probabilities and Financial Mathematics at BSc and MSc levels.

  - title: Intern Quantitative Analyst
    company: Engie
    company_url: 'https://www.engie.com/en'
    company_logo: Engie_logo
    location: Paris, France
    date_start: '2003-03-01'
    date_end: '2003-09-01'
    description: Worked on Forward Gas Contracts prices modeling and developed application to expose prices to traders.

design:
  columns: '2'
---
