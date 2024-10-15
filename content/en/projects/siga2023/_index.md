---
tile:  ""
date: 2024-10-14
author: Kei Iwasaki
---
<script src="https://kit.fontawesome.com/429fe8bdbc.js" crossorigin="anonymous"></script>

### Efficient Visualization of Light Pollution for the Night Sky
<img src="../img/tvcg2021.jpg">

#### Abstract
Artificial light sources make our daily life convenient, but cause a severe problem called light pollution. We propose a novel system for efficient visu- alization of light pollution in the night sky. Numerous methods have been proposed for rendering the sky, but most of these focus on rendering of the daytime or the sunset sky where the sun is the only, or dominant light source. For the visualization of the light pollution, however, we must consider many city light sources on the ground, resulting in excessive computational cost. We address this problem by precomputing a set of intensity distributions for the sky illuminated by city light at various locations and with different atmospheric conditions. We apply a principal component analysis and fast Fourier transform to the precomputed distributions, allowing us to efficiently visualize the extent of the light pollution. Using this method, we can achieve one to two orders of magnitudes faster computation compared to a naive approach that simply accumulates the scattered intensity for each viewing ray. Furthermore, the fast computation allows us to interactively solve the in- verse problem that determines the city light intensity needed to reduce light pollution. Our system provides the user with both a forward and inverse investigation tool for the study and minimization of light pollution.

#### Downloads
<i class="fa-solid fa-file-pdf"></i> <a href="">paper</a> <br>
<i class="fa-solid fa-file-pdf"></i> <a href="">supplemental document</a> <br>

#### Cite
``` bibtex
@ARTICLE{9380921,
  author={Nabata, Kosuke and Iwasaki, Kei},
  journal={IEEE Transactions on Visualization and Computer Graphics}, 
  title={Adaptive Irradiance Sampling for Many-Light Rendering of Subsurface Scattering}, 
  year={2022},
  volume={28},
  number={10},
  pages={3324-3335},
  keywords={Rendering (computer graphics);Scattering;Three-dimensional displays;Monte Carlo methods;Sampling methods;Error analysis;Tuning;Subsurface scattering;BSSRDF;adaptive sampling;many-lights},
  doi={10.1109/TVCG.2021.3066640}}
```

---