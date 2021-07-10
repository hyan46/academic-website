---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Rapid Detection of Hot-Spots via Tensor Decomposition with Applications to
  Crime Rate Data
subtitle: ''
summary: ''
authors:
- Yujie Zhao
- Hao Yan
- Sarah Holte
- Yajun Mei
tags:
- '"Anomaly Detection"'
- '"Social"'
- '"Tensor"'
- '"Video"'
categories: []
date: '2021-01-01'
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
publishDate: '2021-07-10T08:27:10.335182Z'
publication_types:
- '2'
abstract: 'We propose an efficient statistical method (denoted as SSR-Tensor) to robustly
  and quickly detect hot-spots that are sparse and temporal-consistent in a spatial-temporal
  dataset through the tensor decomposition. Our main idea is to first build an SSR
  model to decompose the tensor data into a Smooth global trend mean, Sparse local
  hot-spots and Residuals. Next, tensor decomposition is utilized as follows: basis
  are introduced to describe within-dimension correlation and tensor products are
  used for between-dimension interaction. Then, a combination of LASSO and fused LASSO
  is used to estimate the model parameters, where an efficient recursive estimation
  procedure is developed based on the large-scale convex optimization, where we first
  transform the general LASSO optimization into regular LASSO optimization and apply
  FISTA to solve it with the fastest convergence rate. Finally, a CUSUM procedure
  is applied to detect when and where the hot-spot event occurs. We compare the performance
  of the proposed method in a numerical simulation and a real-world dataset, which
  is a collection of three types of crime rates for U.S. mainland states during the
  year 1965-2014. In both cases, the proposed SSR-Tensor is able to achieve the fast
  detection and accurate localization of the hot-spots.'
publication: '*Journal of Applied Statistics*'
doi: 10.1080/02664763.2021.1874892
---
