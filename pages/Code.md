---
layout: page
title: Code
permalink: /code/
feature-img: "assets/img/codepic.jpg"
tags: [Page]
---

## Finite Element C++ research code:

Based on the original [voom](https://github.com/wsklug/voom) code from Dr. William Klug at UCLA, we have developed an in-house C++ finite element code named voom2 (and voom3) to test the material models and numerical schemes we study in our research. Voom2 has been used, for example, to test and develop our [“Method for the unique identification of hyperelastic material properties using full‐field measures.”](https://onlinelibrary.wiley.com/doi/abs/10.1002/cnm.2866) If you are interested in using this code, please feel free to download it from our public github repository at:

[https://github.com/luigiemp/voom2](https://github.com/luigiemp/voom2)

If you decide to use this code in your research, please cite the paper above.


 
## Cardiac kinematics Phantom:

We have recently developed a method to [“Estimating Aggregate Cardiomyocyte Strain Using In Vivo Diffusion and Displacement Encoded MRI.”](https://ieeexplore.ieee.org/abstract/document/8792099) In order to test our method and quantify the effect of noise and of the image processing pipeline, we have developed a code to simulate a mid left ventricular (LV) slice motion in an analytical phantom and generate the corresponding DENSE data. By using the phantom analytical solution as “ground truth”, we have been able to identify the image requirements for computing strains within a prescribed confidence interval. The code to simulate mid LV motion and generate the corresponding MR DENSE images can be downloaded from our public github repository here:

[https://github.com/luigiemp/CardiacKinematicsPhantom](https://github.com/luigiemp/CardiacKinematicsPhantom)

If you decide to use this code in your research, please cite the paper above.

