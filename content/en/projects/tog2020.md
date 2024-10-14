---
tile:  "RISBPT"
date: 2024-10-14 
author: Kei Iwasaki
---
### Resampling-aware Weighting Functions for Bidirectional Path Tracing using Multiple Light Sub-paths

<img src="../img/tog2020.png">

#### Abstract
Bidirectional path tracing (BPT) with multiple importance sampling (MIS)
is a popular technique for rendering realistic images. Recently, it has been
shown that BPT can be improved by preparing multiple light sub-paths and
by resampling a small number of light sub-paths from them to generate full
paths with large contribution. Traditionally, for MIS weights, the balance
heuristic has widely been used to minimize the upper bound of variance,
where each full path is weighted in proportion to the probability of the
path. Although the probability of the path can change due to the resampling
process, the weighting functions used in the previous methods remain unaf-
fected by the change in probability, resulting in less efficiency. To address
this problem, we propose new weighting functions for BPT with multiple
light sub-paths. Our main contribution is a precise formulation of the vari-
ance and the derivation of the weighting functions that can appropriately
treat the change in probability. We demonstrate that our weighting functions
significantly improve the image quality. We will release a simple version of
our implementation as open source to ensure reproducibility.

### Code



---
