---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Weakly Correlated Profile Monitoring Based on Sparse Multi-Channel Functional
  Principal Component Analysis
subtitle: ''
summary: ''
authors:
- Chen Zhang
- Hao Yan
- Seungho Lee
- Jianjun Shi
tags:
- '"Anomaly Detection"'
- '"Functional Data"'
- '"Manufacturing"'
- '"Profiles"'
- '"Sparse Learning"'
categories: []
date: '2018-10-01'
lastmod: 2021-07-09T12:25:40-07:00
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
publishDate: '2021-07-10T08:27:09.683810Z'
publication_types:
- '2'
abstract: 'Although several works have been proposed for multi-channel profile monitoring,
  two additional challenges are yet to be addressed: (i) how to model complex correlations
  of multi-channel profiles when different profiles have different features (i.e.,
  weakly or sparsely correlated); (ii) how to efficiently detect sparse changes occurring
  in only a small segment of a few profiles. To fill this research gap, our contributions
  are twofold. First, we propose a novel Sparse Multi-channel Functional Principal
  Component Analysis (SMFPCA) to model multi-channel profiles. SMFPCA can not only
  flexibly describe the correlation structure of multiple, or even high-dimensional,
  profiles with distinct features, but also achieve sparse PCA scores which are easily
  interpretable. Second, we propose an efficient convergence-guaranteed optimization
  algorithm to solve SMFPCA in real time based on the block coordinate descent algorithm.
  Third, as the SMFPCA scores can naturally identify sparse out-of-control (OC) patterns,
  we use the scores to construct a monitoring scheme which provides increased sensitivity
  to sparse OC changes. Numerical studies together with a real case study in a manufacturing
  system demonstrate the effectiveness of the developed methodology.'
publication: '*IISE Transactions*'
doi: 10.1080/24725854.2018.1451012
---
