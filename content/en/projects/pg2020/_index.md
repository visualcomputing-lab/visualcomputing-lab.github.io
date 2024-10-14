---
tile:  ""
date: 2024-10-14
author: Kei Iwasaki
---
### 
<img src="../img/cgf20.jpg">


#### Abstract
Recent advances in bidirectional path tracing (BPT) reveal that the use of multiple light sub-paths and the resampling of a small number of these can improve the efficiency of BPT. By increasing the number of pre-sampled light sub-paths, the possibility of generating light paths that provide large contributions can be better explored and this can alleviate the correlation of light paths due to the reuse of pre-sampled light sub-paths by all eye sub-paths. The increased number of pre-sampled light subpaths, however, also incurs a high computational cost. In this paper, we propose a two-stage resampling method for BPT to efficiently handle a large number of pre-sampled light sub-paths. We also derive a weighting function that can treat the changes in path probability due to the two-stage resampling. Our method can handle a two orders of magnitude larger number of presampled light sub-paths than previous methods in equal-time rendering, resulting in stable and better noise reduction than state-of-the-art methods.
###  

---
