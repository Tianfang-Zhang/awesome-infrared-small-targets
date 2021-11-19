# Awesome Infrared Small Targets

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Tianfang-Zhang/awesome-infrared-small-targets)

### Table of Contents

  - [Background Suppression-Based Methods](#background-suppression-based-methods)
  - [Human Visual System-Based Methods](#human-visual-system-based-methods)
  - [Optimization-Based Methods](#optimization-based-methods)
    - [Matrix: Single-Subspace](#matrix-single-subspace)
    - [Matrix: Multi-Subspace](#matrix-multi-subspace)
    - [Tensor](#tensor)
  - [Deep Learning-Based Methods](#deep-learning-based-methods)
  - [Datasets](#datasets)


## [Background Suppression-Based Methods](#table-of-contents)
- **Tophat**, Morphology-based algorithm for point target detection in infrared backgrounds. 
  + Tom V T, Peli T, Leung M, et al. Signal and Data Processing of Small Targets, **1993**. International Society for Optics and Photonics, **1993**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/1954/0000/Morphology-based-algorithm-for-point-target-detection-in-infrared-backgrounds/10.1117/12.157758.short)

- **MaxMedian**, Max-mean and max-median filters for detection of small targets. 
  + Deshpande S D, Er M H, Venkateswarlu R, et al. Signal and Data Processing of Small Targets, **1999**. International Society for Optics and Photonics, **1999**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/3809/0000/Max-mean-and-mamedian-filters-for-detection-of-small/10.1117/12.364049.short?SSO=1)

- **PFT**, Spatio-temporal saliency detection using phase spectrum of Quaternion Fourier Transform. 
  + Guo C, Ma Q, Zhang L. **CVPR, 2008**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/4587715)

- **LACM-LSK**, Robust infrared small target detection using local steering kernel reconstruction. 
  + Li Y, Zhang Y. **Pattern Recognition, 2018**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S0031320317304983)

- Infrared Small Target Detection by Density Peaks Searching and Maximum-Gray Region Growing. 
  + Huang S, Peng Z, Wang Z, et al. **TGRS Letters, 2019**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8715427) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/Suqi-Huang/DensityPeaksIR)

- Structure-Adaptive Clutter Suppression for Infrared Small Target Detection: Chain-Growth Filtering. 
  + Huang S, Liu Y, He Y, et al. **Remote Sensing, 2020**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/12/1/47)

## [Human Visual System-Based Methods](#table-of-contents)

- **LCM**, A Local Contrast Method for Small Infrared Target Detection. 
  + Chen C L P, Li H, Wei Y, et al. **TGRS, 2013**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/6479296)

- **ILCM**, A Robust Infrared Small Target Detection Algorithm Based on Human Visual System. 
  + Han J, Ma Y, Zhou B, et al. **TGRS Letters, 2014**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/6819810)

- **LSM**, An Efficient Infrared Small Target Detection Method Based on Visual Contrast Mechanism. 
  + Chen Y, Xin Y. **TGRS Letters, 2016**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/7466097)
  
- **WLDM**, Small infrared target detection based on weighted local difference measure. 
  + Deng H, Sun X, Liu M, et al. **TGRS, 2016**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/7460907)

- **IDoGb**, An infrared small target detecting algorithm based on human visual system. 
  + Han J, Ma Y, Huang J, et al. **TGRS Letters, 2016**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/7399358)

- **NLCM**, Effective infrared small target detection utilizing a novel local contrast method.
  + Qin Y, Li B. **TGRS Letters, 2016**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/7725517)

- **MPCM**, Multiscale patch-based contrast measure for small infrared target detection. 
  + Wei Y, You X, Li H. **Pattern Recognition, 2016**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S0031320316300358)

- **LDM**, Entropy-based window selection for detecting dim and small infrared targets. 
  + Deng H, Sun X, Liu M, et al. **Pattern Recognition, 2017**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S0031320316301947)

- **DECM**, Derivative entropy-based contrast measure for infrared small-target detection. 
  + Bai X, Bi Y. **TGRS, 2018**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8245877)

- **RLCM**, Infrared small target detection utilizing the multiscale relative local contrast measure. 
  + Han J, Liang K, Zhou B, et al. **TGRS Letters, 2018**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8289318)

- **WMFD**, Infrared small target detection based on flux density and direction diversity in gradient vector field. 
  + Liu D, Cao L, Li Z, et al. **IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2018**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8360016)

- **HB-MLCM**, High-boost-based multiscale local contrast measure for infrared small target detection. **TGRS Letters, 2017**.
  + Shi Y, Wei Y, Yao H, et al.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8125583)

- Infrared Small Target Detection Based on Derivative Dissimilarity Measure. 
  + Cao X, Rong C, Bai X. **IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2019**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8737845)


## [Optimization-Based Methods](#table-of-contents)

### [Matrix: Single-Subspace](#table-of-contents)

- **IPI**, Infrared patch-image model for small target detection in a single image.
  + Gao C, Meng D, Yang Y, et al. **TIP, 2013**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/6595533) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/gaocq/IPI-for-small-target-detection)

- **NIPPS**, Non-negative infrared patch-image model: Robust target-background separation via partial sum minimization of singular values.
  + Dai Y, Wu Y, Song Y, et al. **Infrared Physics & Technology, 2017**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S1350449516303723) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/YimianDai/DENTIST)

- **TV-PCP**, Infrared dim target detection based on total variation regularization and principal component pursuit.
  + Wang X, Peng Z, Kong D, et al. **Image and Vision Computing, 2017**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S0262885617300756) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://wang-xiaoyang.github.io/publication/2017-07-01-paper-title-number-2)

- **NRAM**, Infrared small target detection via non-convex rank approximation minimization joint l2, 1 norm.
  + Zhang L, Peng L, Zhang T, et al. **Remote Sensing, 2018**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/10/11/1821) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/Lanneeee/NRAM)

- **NOLC**, Infrared small target detection based on non-convex optimization with Lp-norm constraint.
  + Zhang T, Wu H, Liu Y, et al. **Remote Sensing, 2019**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/11/5/559) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/Tianfang-Zhang/NOLC)


### [Matrix: Multi-Subspace](#table-of-contents)

- **LRSR**, Small infrared target detection based on low-rank and sparse representation.
  + He Y J, Li M, Zhang J L, et al. **Infrared Physics & Technology, 2015**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S1350449514002576)

- **SMSL**, Infrared dim and small target detection based on stable multisubspace learning in heterogeneous scene.
  + Wang X, Peng Z, Kong D, et al. **TGRS, 2017**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/7999276) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://wang-xiaoyang.github.io/publication/2017-08-01-paper-title-number-1)

- **SRWS**, Infrared small target detection via self-regularized weighted sparse model.
  + Zhang T, Peng Z, Wu H, et al. **Neurocomputing, 2021**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S0925231220313461) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/Tianfang-Zhang/SRWS)

### [Tensor](#table-of-contents)

- **RIPT**, Reweighted infrared patch-tensor model with both nonlocal and local priors for single-frame small target detection.
  + Dai Y, Wu Y. [J]. **IEEE journal of selected topics in applied earth observations and remote sensing, 2017**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/7932858) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/YimianDai/DENTIST)

- **PSTNN**, Infrared small target detection based on partial sum of the tensor nuclear norm.
  + Zhang L, Peng Z. **Remote Sensing, 2019**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/11/4/382) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/Lanneeee/Infrared-Small-Target-Detection-based-on-PSTNN)

- Infrared Small Target Detection via Low-Rank Tensor Completion With Top-Hat Regularization.
  + H. Zhu, S. Liu, L. Deng, Y. Li and F. Xiao. **TGRS, 2020**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8867952)

- Infrared dim target detection via mode-k1k2 extension tensor tubal rank under complex ocean environment.
  + Z. Cao, X. Kong, Q. Zhu, S. Cao and Z. Peng. **SPRS Journal of Photogrammetry and Remote Sensing， 2021**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/pii/S0924271621002392)

- Infrared Small Target Detection via Nonconvex Tensor Fibered Rank Approximation.
  + X. Kong, C. Yang, S. Cao, C. Li, Z. Peng. **TGRS， 2021**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/9394596)


## [Deep Learning-Based Methods](#table-of-contents)

- **MDvsFA cGan**, Miss detection vs. false alarm: Adversarial learning for small object segmentation in infrared images.
  + Wang H, Zhou L, Wang L. **ICCV, 2019**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content_ICCV_2019/html/Wang_Miss_Detection_vs._False_Alarm_Adversarial_Learning_for_Small_Object_ICCV_2019_paper.html) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/wanghuanphd/MDvsFA_cGAN)

- **ACM**, Asymmetric contextual modulation for infrared small target detection.
  + Dai Y, Wu Y, Zhou F, et al. **WACV, 2021**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content/WACV2021/html/Dai_Asymmetric_Contextual_Modulation_for_Infrared_Small_Target_Detection_WACV_2021_paper.html) [![](https://img.shields.io/badge/Code-MXNet-orange)](https://github.com/YimianDai/open-acm) [![](https://img.shields.io/badge/Code-PyTorch-green)](https://github.com/Tianfang-Zhang/acm-pytorch)

- TBC-Net: A real-time detector for infrared small target detection using semantic constraint.
  + M. Zhao, L. Cheng, X. Yang, P. Feng, L. Liu and N. Wu. **arXiv, 2019**
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2001.05852)

- **ALCNet** Attentional Local Contrast Networks for Infrared Small Target Detection.
  + Y. Dai, Y. Wu, F. Zhou, K. J. I. T. o. G. Barnard and R. Sensing. **TGRS, 2021**
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/9314219) [![](https://img.shields.io/badge/Code-MXNet-orange)](https://github.com/YimianDai/open-alcnet)

- **DNANet** Dense Nested Attention Network for Infrared Small Target Detection.
  + B. Li, C. Xiao, L. Wang, Y. Wang, Z. Lin, M. Li, et al. **arXiv, 2021**
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2106.00487) [![](https://img.shields.io/badge/Code-PyTorch-green)](https://github.com/YeRen123455/Infrared-Small-Target-Detection)

- Infrared Small-Dim Target Detection with Transformer under Complex Backgrounds
  + F. Liu, C. Gao, F. Chen, D. Meng, W. Zuo and X. Gao. **arXiv, 2021**
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2109.14379)

- EAAU-Net: Enhanced asymmetric attention U-Net for infrared small target detection.
  + X. Tong, B. Sun, J. Wei, Z. Zuo and S. Su. **Remote Sensing, 2021**
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/13/16/3200)

- AGPCNet: Attention-Guided Pyramid Context Networks for Infrared Small Target Detection.
  + Tianfang Zhang, Siying Cao, Tian Pu, Zhenming Peng. **arXiv, 2021**
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2111.03580) [![](https://img.shields.io/badge/Code-PyTorch-green)](https://github.com/Tianfang-Zhang/AGPCNet)


## [Datasets](#table-of-contents)

- **MDFA**, Miss detection vs. false alarm: Adversarial learning for small object segmentation in infrared images.
  + Wang H, Zhou L, Wang L. **ICCV, 2019**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content_ICCV_2019/html/Wang_Miss_Detection_vs._False_Alarm_Adversarial_Learning_for_Small_Object_ICCV_2019_paper.html) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/wanghuanphd/MDvsFA_cGAN)

- **SIRST**, Asymmetric contextual modulation for infrared small target detection.
  + Dai Y, Wu Y, Zhou F, et al. **WACV, 2021**.
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content/WACV2021/html/Dai_Asymmetric_Contextual_Modulation_for_Infrared_Small_Target_Detection_WACV_2021_paper.html) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/YimianDai/sirst) 

- **SIRST-Aug**, AGPCNet: Attention-Guided Pyramid Context Networks for Infrared Small Target Detection.
  + Tianfang Zhang, Siying Cao, Tian Pu, Zhenming Peng. **arXiv, 2021**
  + [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2111.03580) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/Tianfang-Zhang/AGPCNet)

-----
Note: 
- ![](https://img.shields.io/badge/Code-PyTorch-orange) represents offical code.
- ![](https://img.shields.io/badge/Code-PyTorch-green) represents reproduced code.