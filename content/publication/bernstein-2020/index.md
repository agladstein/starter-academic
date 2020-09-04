---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Jupyter notebook-based tools for building structured datasets from the Sequence
  Read Archive [version 2; peer review: 2 approved]'
subtitle: ''
summary: ''
authors:
- M N Bernstein
- A Gladstein
- K Z Latt
- E Clough
- B Busby
- A Dillman
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-09-04T17:25:37-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-09-04T22:28:40.531710Z'
publication_types:
- 2
abstract: The Sequence Read Archive (SRA) is a large public repository that stores
  raw next-generation sequencing data from thousands of diverse scientific investigations.  Despite
  its promise, reuse and re-analysis of SRA data has been challenged by the heterogeneity
  and poor quality of the metadata that describe its biological samples. Recently,
  the MetaSRA project standardized these metadata by annotating each sample with terms
  from biomedical ontologies. In this work, we present a pair of Jupyter notebook-based
  tools that utilize the MetaSRA for building structured datasets from the SRA in
  order to facilitate secondary analyses of the SRA’s human RNA-seq data. The first
  tool, called the Case-Control Finder, finds suitable case and control samples for
  a given disease or condition where the cases and controls are matched by tissue
  or cell type.  The second tool, called the Series Finder, finds ordered sets of
  samples for the purpose of addressing biological questions pertaining to changes
  over a numerical property such as time. These tools were the result of a three-day-long
  NCBI Codeathon in March 2019 held at the University of North Carolina at Chapel
  Hill.
publication: '*F1000Research*'
doi: 10.12688/f1000research.23180.2
---
