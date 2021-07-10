---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A Wavelet-Based Penalized Mixed-Effects Decomposition for Multichannel Profile
  Detection of In-Line Raman Spectroscopy
subtitle: ''
summary: ''
authors:
- Xiaowei Yue
- Hao Yan
- Jin Gyu Park
- Zhiyong Liang
- Jianjun Shi
tags:
- '"Anomaly Detection"'
- '"Functional Data"'
- '"Manufacturing"'
- '"Material"'
- '"Profiles"'
categories: []
date: '2018-07-01'
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
publishDate: '2021-07-10T08:27:09.091756Z'
publication_types:
- '2'
abstract: 'Modeling and analysis of profiles, especially high-dimensional nonlinear
  profiles, is an important and challenging topic in statistical process control.
  Conventional mixed-effects models have several limitations in solving the multichannel
  profile detection problems for in-line Raman spectroscopy, such as the inability
  to separate defective information from random effects, computational inefficiency,
  and inability to handle high-dimensional extracted coefficients. In this paper,
  a new wavelet-based penalized mixed-effects decomposition (PMD) method is proposed
  to solve the multichannel profile detection problem in Raman spectroscopy. The proposed
  PMD exploits a regularized high-dimensional regression with linear constraints to
  decompose the profiles into four parts: fixed effects, normal effects, defective
  effects, and signal-dependent noise. An optimization algorithm based on the accelerated
  proximal gradient (APG) is developed to do parameter estimation efficiently for
  the proposed model. Finally, the separated fixed effects coefficients, normal effects
  coefficients, and defective effects coefficients can be used to extract the quality
  features of fabrication consistency, within-sample uniformity, and defect information,
  respectively. Using a surrogated data analysis and a case study, we evaluated the
  performance of the proposed PMD method and demonstrated a better detection power
  with less computational time. Note to Practitioners - This paper was motivated by
  the need of implementing multichannel profile detection for Raman spectra to realize
  in-line process monitoring and quality control of continuous manufacturing of carbon
  nanotube (CNT) buckypaper. Existing approaches, such as the mixed-effects model
  or the smooth-sparse decomposition method, cannot separate defective information
  in random effects effectively. This paper develops a penalized mixed-effects decomposition
  which decomposes Raman spectra into four components: fixed effects, normal effects,
  defective effects, and signal-dependent noise, respectively. The first three components
  can be applied to monitor the fabrication consistency, degree of uniformity, and
  defect information of buckypaper, respectively. With this new approach, several
  quality features can be monitored simultaneously and the algorithm based on the
  accelerated proximal gradient (APG) method can satisfy the computation speed requirement
  of in-line monitoring. This paper provides a solid foundation for in-line process
  monitoring and quality control for scalable nanomanufacturing of CNT buckypaper.
  Furthermore, the developed methodology can be applied in the decomposition of other
  signal systems with fixed, normal, and defective effects.'
publication: '*IEEE Transactions on Automation Science and Engineering*'
doi: 10.1109/TASE.2017.2772218
---
