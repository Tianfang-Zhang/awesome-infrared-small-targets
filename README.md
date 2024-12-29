# Awesome Infrared Small Targets  
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Tianfang-Zhang/awesome-infrared-small-targets)

We will continue to focus on this field and update relevant information.

Since 2024, we have been collecting papers **WITH CODE**. If you have any paper with code or an awesome ISTD project that is missing from this repository, please contact us.

Keywords: Infrared small targets detection, infrared small targets segmentation.


## [Table of Contents](#table-of-contents)
- [Awesome Infrared Small Targets](#awesome-infrared-small-targets)
  - [Table of Contents](#table-of-contents)
  - [Background Suppression-Based Methods](#background-suppression-based-methods)
  - [Human Visual System-Based Methods](#human-visual-system-based-methods)
  - [Optimization-Based Methods](#optimization-based-methods)
    - [Matrix: Single-Subspace](#matrix-single-subspace)
    - [Matrix: Multi-Subspace](#matrix-multi-subspace)
    - [Tensor: Single-Frame](#tensor-single-frame)
    - [Tensor: Multi-Frame](#tensor-multi-frame)
  - [Deep Learning-Based Methods](#deep-learning-based-methods)
    - [Single-Frame](#single-frame)
    - [Multi-Frame](#multi-frame)
  - [Deep Unfolding-Based Methods](#deep-unfolding-based-methods)
  - [Datasets](#datasets)
    - [Datasets: Single-Frame](#datasets-single-frame)
    - [Datasets: Multi-Frame](#datasets-multi-frame)
  - [Recommended Benchmarks](#recommended-benchmarks)
  - [Recommended Surveys](#recommended-surveys)
- [Acknowledgement](#acknowledgement)


<!-- ## SOTA Methods with Code

| Title  | Venue | Date  | Code |  Topic  |
|:------|:------:|:------:|:------:|:------:| -->






## [Background Suppression-Based Methods](#table-of-contents)

- **Tophat**, Morphology-based algorithm for point target detection in infrared backgrounds.
  - Tom V T, Peli T, Leung M, et al. Signal and Data Processing of Small Targets. International Society for Optics and Photonics, **1993**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/1954/0000/Morphology-based-algorithm-for-point-target-detection-in-infrared-backgrounds/10.1117/12.157758.short)

- **MaxMedian**, Max-mean and max-median filters for detection of small targets.
  - Deshpande S D, Er M H, Venkateswarlu R, et al. Signal and Data Processing of Small Targets. International Society for Optics and Photonics, **1999**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/3809/0000/Max-mean-and-mamedian-filters-for-detection-of-small/10.1117/12.364049.short?SSO=1)

- **PFT**, Spatio-temporal saliency detection using phase spectrum of Quaternion Fourier Transform.
  - Guo C, Ma Q, Zhang L. **CVPR, 2008**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/4587715)

- **LACM-LSK**, Robust infrared small target detection using local steering kernel reconstruction.
  - Li Y, Zhang Y. **PR, 2018**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S0031320317304983)

- Infrared Small Target Detection by Density Peaks Searching and Maximum-Gray Region Growing.
  - Huang S, Peng Z, Wang Z, et al. **GRSL, 2019**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8715427) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/Suqi-Huang/DensityPeaksIR)

- **FKRW**, Infrared Small Target Detection Based on Facet Kernel and Random Walker.
  - Y. Qin, L. Bruzzone, C. Gao and B. Li. **TGRS, 2019**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/8705367) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/tsinjiao/InfraredTargetDectectionFKRW)

- Structure-Adaptive Clutter Suppression for Infrared Small Target Detection: Chain-Growth Filtering.
  - Huang S, Liu Y, He Y, et al. **Remote Sensing, 2020**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/12/1/47)

- Infrared small-target detection based on multiple morphological profiles.
  - M. Zhao, L. Li, W. Li, et al. **TGRS, 2020**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/9200791)

## [Human Visual System-Based Methods](#table-of-contents)

- **LCM**, A Local Contrast Method for Small Infrared Target Detection.
  - Chen C L P, Li H, Wei Y, et al. **TGRS, 2013**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/6479296)

- **ILCM**, A Robust Infrared Small Target Detection Algorithm Based on Human Visual System.
  - Han J, Ma Y, Zhou B, et al. **GRSL, 2014**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/6819810)

- **LSM**, An Efficient Infrared Small Target Detection Method Based on Visual Contrast Mechanism.
  - Chen Y, Xin Y. **GRSL, 2016**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/7466097)
  
- **WLDM**, Small infrared target detection based on weighted local difference measure.
  - Deng H, Sun X, Liu M, et al. **TGRS, 2016**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/7460907)

- **IDoGb**, An infrared small target detecting algorithm based on human visual system.
  - Han J, Ma Y, Huang J, et al. **GRSL, 2016**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/7399358)

- **NLCM**, Effective infrared small target detection utilizing a novel local contrast method.
  - Qin Y, Li B. **GRSL, 2016**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/7725517)

- **MPCM**, Multiscale patch-based contrast measure for small infrared target detection.
  - Wei Y, You X, Li H. **PR, 2016**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S0031320316300358)

- **LDM**, Entropy-based window selection for detecting dim and small infrared targets.
  - Deng H, Sun X, Liu M, et al. **PR, 2017**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S0031320316301947)

- **DECM**, Derivative entropy-based contrast measure for infrared small-target detection.
  - Bai X, Bi Y. **TGRS, 2018**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8245877)

- **RLCM**, Infrared small target detection utilizing the multiscale relative local contrast measure.
  - Han J, Liang K, Zhou B, et al. **GRSL, 2018**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8289318)

- **WMFD**, Infrared small target detection based on flux density and direction diversity in gradient vector field.
  - Liu D, Cao L, Li Z, et al. **JSTARS, 2018**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8360016)

- **HB-MLCM**, High-boost-based multiscale local contrast measure for infrared small target detection.
  - Shi Y, Wei Y, Yao H, et al. **GRSL, 2017**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8125583)

- Infrared Small Target Detection Based on Derivative Dissimilarity Measure.
  - Cao X, Rong C, Bai X. **JSTARS, 2019**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8737845)

- Infrared Small Target Detection Via Center-surround Gray Difference Measure with Local Image Block Analysis.
  - Y. Li, Z. Li, Y. Shen and Z. Guo. **TAES, 2022**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/9822383/)

- Weighted Local Ratio-Difference Contrast Method for Detecting an Infrared Small Target against Ground–Sky Background.
  - H. Wei, P. Ma, D. Pang et al. **Remote Sensing, 2022**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/14/22/5636)

## [Optimization-Based Methods](#table-of-contents)

### [Matrix: Single-Subspace](#table-of-contents)

- **IPI**, Infrared patch-image model for small target detection in a single image.
  - Gao C, Meng D, Yang Y, et al. **TIP, 2013**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/6595533) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/gaocq/IPI-for-small-target-detection)

- **NIPPS**, Non-negative infrared patch-image model: Robust target-background separation via partial sum minimization of singular values.
  - Dai Y, Wu Y, Song Y, et al. **Infrared Physics & Technology, 2017**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S1350449516303723) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/YimianDai/DENTIST)

- **TV-PCP**, Infrared dim target detection based on total variation regularization and principal component pursuit.
  - Wang X, Peng Z, Kong D, et al. **Image and Vision Computing, 2017**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S0262885617300756) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://wang-xiaoyang.github.io/publication/2017-07-01-paper-title-number-2)

- **NRAM**, Infrared small target detection via non-convex rank approximation minimization joint l2, 1 norm.
  - Zhang L, Peng L, Zhang T, et al. **Remote Sensing, 2018**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/10/11/1821) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/Lanneeee/NRAM)

- **NOLC**, Infrared small target detection based on non-convex optimization with Lp-norm constraint.
  - Zhang T, Wu H, Liu Y, et al. **Remote Sensing, 2019**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/11/5/559) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/Tianfang-Zhang/NOLC)

- **RS1/2NIPI**, Detection of Small Target Using Schatten 1/2 Quasi-Norm Regularization with Reweighted Sparse Enhancement in Complex Infrared Scenes.
  - F. Zhou, Y. Wu, Y. Dai and P. Wang. **Remote Sensing, 2019**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/11/17/2058)

### [Matrix: Multi-Subspace](#table-of-contents)

- **LRSR**, Small infrared target detection based on low-rank and sparse representation.
  - He Y J, Li M, Zhang J L, et al. **Infrared Physics & Technology, 2015**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S1350449514002576)

- **SMSL**, Infrared dim and small target detection based on stable multisubspace learning in heterogeneous scene.
  - Wang X, Peng Z, Kong D, et al. **TGRS, 2017**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/7999276) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://wang-xiaoyang.github.io/publication/2017-08-01-paper-title-number-1)

- **SRWS**, Infrared small target detection via self-regularized weighted sparse model.
  - Zhang T, Peng Z, Wu H, et al. **Neurocomputing, 2021**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/abs/pii/S0925231220313461) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/Tianfang-Zhang/SRWS)

### [Tensor: Single-Frame](#table-of-contents)

- **RIPT**, Reweighted infrared patch-tensor model with both nonlocal and local priors for single-frame small target detection.
  - Dai Y, Wu Y. **JSTARS, 2017**.  
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/7932858) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/YimianDai/DENTIST)

- **PSTNN**, Infrared small target detection based on partial sum of the tensor nuclear norm.
  - Zhang L, Peng Z. **Remote Sensing, 2019**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/11/4/382) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/Lanneeee/Infrared-Small-Target-Detection-based-on-PSTNN)

- **TCTHR**, Infrared Small Target Detection via Low-Rank Tensor Completion With Top-Hat Regularization.
  - H. Zhu, S. Liu, L. Deng, Y. Li and F. Xiao. **TGRS, 2020**.  
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/8867952)

- **METTR**, Infrared dim target detection via mode-k1k2 extension tensor tubal rank under complex ocean environment.
  - Z. Cao, X. Kong, Q. Zhu, S. Cao and Z. Peng. **ISPRS Journal of Photogrammetry and Remote Sensing, 2021**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/pii/S0924271621002392)

- **LogTFNN**, Infrared Small Target Detection via Nonconvex Tensor Fibered Rank Approximation.
  - X. Kong, C. Yang, S. Cao, C. Li, Z. Peng. **TGRS, 2021**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/9394596)

- **CMPG**, Infrared Small Target Detection via L0 Sparse Gradient Regularized Tensor Spectral Support Low-Rank Decomposition.
  - F. Zhou, M. Fu, Y. Duan et al. **TAES, 2022**.  
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/9903329)

### [Tensor: Multi-Frame](#table-of-contents)

- **STT**: Small Target Detection in Infrared Videos Based on Spatio-Temporal Tensor Model.
  - H. -K. Liu, L. Zhang and H. Huang. **TGRS, 2020**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/9088265)

- **ECA-STT**: Edge and Corner Awareness-Based Spatial–Temporal Tensor Model for Infrared Small-Target Detection.
  - P. Zhang, L. Zhang, X. Wang, F. Shen, T. Pu and C. Fei. **TGRS, 2022**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/9279305) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/ELOESZHANG/ECA-STT-for-IR-small-target-detection)

- **ASTTV-NTLA**: Nonconvex Tensor Low-Rank Approximation for Infrared Small Target Detection.
  - T. Liu et al. **TGRS, 2022**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/9626011) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/LiuTing20a/ASTTV-NTLA)

- **IMNN-LWEC**: A Novel Infrared Small Target Detection Based on Spatial–Temporal Tensor Model.
  - Y. Luo, X. Li, S. Chen et al. **TGRS, 2022**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/9991168/)

- **NPSTT**, Infrared Small Target Detection Using Nonoverlapping Patch Spatial–Temporal Tensor Factorization With Capped Nuclear Norm Regularization.
  - G. Wang, B. Tao, X. Kong and Z. Peng. **TGRS, 2022**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/9606877)

- **SRSTT**, Sparse Regularization-Based Spatial-Temporal Twist Tensor Model for Infrared Small Target Detection.
  - J. Li, P. Zhang, L. Zhang and Z. Zhang. **TGRS, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](http://ieeexplore.ieee.org/document/10007842)

- **4-D TT/TR**, Infrared Small Target Detection Using Spatiotemporal 4-D Tensor Train and Ring Unfolding.
  - F. Wu, H. Yu, A. Liu, J. Luo and Z. Peng. **TGRS, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10156866) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/fengyiwu98/4D_ISTD)

- **WSWTNN-PnP**, Combining Deep Denoiser and Low-rank Priors for Infrared Small Target Detection.
  - T. Liu, Q. Yin, J. Yang, Y. Wang and W. An. **PR, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/pii/S003132032200663X) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/LiuTing20a/WSWTNN-PnP)

- **3DSTPM**, Infrared Small Target Detection Combining Deep Spatial–Temporal Prior With Traditional Priors.
  - Z. Zhang, P. Gao, S. Ji, X. Wang, and P. Zhang. **TGRS, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10275009)

## [Deep Learning-Based Methods](#table-of-contents)

### [Single-Frame](#table-of-contents)

- **MDvsFA cGan**, Miss detection vs. false alarm: Adversarial learning for small object segmentation in infrared images.
  - Wang H, Zhou L, Wang L. **ICCV, 2019**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content_ICCV_2019/html/Wang_Miss_Detection_vs._False_Alarm_Adversarial_Learning_for_Small_Object_ICCV_2019_paper.html) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/wanghuanphd/MDvsFA_cGAN)

- **ACM**, Asymmetric contextual modulation for infrared small target detection.
  - Dai Y, Wu Y, Zhou F, et al. **WACV, 2021**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content/WACV2021/html/Dai_Asymmetric_Contextual_Modulation_for_Infrared_Small_Target_Detection_WACV_2021_paper.html) [![](https://img.shields.io/badge/Code-MXNet-orange)](https://github.com/YimianDai/open-acm) [![](https://img.shields.io/badge/Code-PyTorch-green)](https://github.com/Tianfang-Zhang/acm-pytorch)

- **TBC-Net**: A real-time detector for infrared small target detection using semantic constraint.
  - M. Zhao, L. Cheng, X. Yang, P. Feng, L. Liu and N. Wu. **arXiv, 2019**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2001.05852)

- **ALCNet**, Attentional Local Contrast Networks for Infrared Small Target Detection.
  - Y. Dai, Y. Wu, F. Zhou, K. J. I. T. o. G. Barnard and R. Sensing. **TGRS, 2021**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/9314219) [![](https://img.shields.io/badge/Code-MXNet-orange)](https://github.com/YimianDai/open-alcnet)

- **DNANet**, Dense Nested Attention Network for Infrared Small Target Detection.
  - B. Li, C. Xiao, L. Wang, Y. Wang, Z. Lin, M. Li, et al. **TIP, 2022**
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/iel7/83/4358840/09864119.pdf) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/YeRen123455/Infrared-Small-Target-Detection)

- Infrared Small-Dim Target Detection with Transformer under Complex Backgrounds.
  - F. Liu, C. Gao, F. Chen, D. Meng, W. Zuo and X. Gao. **TIP, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10298041)

- **EAAU-Net**: Enhanced asymmetric attention U-Net for infrared small target detection.
  - X. Tong, B. Sun, J. Wei, Z. Zuo and S. Su. **Remote Sensing, 2021**
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/13/16/3200)

- **AGPCNet**, Attention-Guided Pyramid Context Networks for Infrared Small Target Detection.
  - Tianfang Zhang, Lei Li, Siying Cao, Tian Pu, Zhenming Peng. **TAES, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2111.03580) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/Tianfang-Zhang/AGPCNet)

- **IRSTFormer**: A Hierarchical Vision Transformer for Infrared Small Target Detection.
  - G. Chen, W. Wang and S. Tan. **Remote Sensing, 2022**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/14/14/3258/pdf)

- **APANet**, Novel Asymmetric Pyramid Aggregation Network for Infrared Dim and Small Target Detection.
  - G. Lv, L. Dong, J. Liang and W. Xu. **Remote Sensing, 2022**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/14/22/5643/pdf)

- **FC3-Net** Exploring Feature Compensation and Cross-level Correlation for Infrared Small Target Detection.
  - M. Zhang, et al. **ACM MM, 2022**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://dl.acm.org/doi/10.1145/3503161.3548264) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/IPIC-Lab/SIRST-Detection-FC3-Net)

- Prior-Guided Data Augmentation for Infrared Small Target Detection.
  - A. Wang, W. Li, Z. Huang et al. **JSTARS, 2022**
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/9954129/)

- **IAANet**, Interior attention-aware network for infrared small target detection.
  - A. Wang, W. Li, Z. Huang et al. **TGRS, 2022**
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/9745054/) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/kwwcv/iaanet)

- **ISNet**: Shape matters for infrared small target detection.
  - M. Zhang, R. Zhang, Y. Yang et al. **CVPR, 2022**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_ISNet_Shape_Matters_for_Infrared_Small_Target_Detection_CVPR_2022_paper.pdf)

- **UIUNet**: U-Net in U-Net for Infrared Small Object Detection.
  - X. Wu, D. Hong, J. Chanussot. **TIP, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/9989433) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/danfenghong/IEEE_TIP_UIU-Net)



- **MTUNet**: Multilevel TransUNet for Space-Based Infrared Tiny Ship Detection.
  - T. Wu et al. **TGRS, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10011449) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/TianhaoWu16/Multi-level-TransUNet-for-Space-based-Infrared-Tiny-ship-Detection)

- **LESPS**: Mapping Degeneration Meets Label Evolution: Learning Infrared Small Target Detection with Single Point Supervision.
  - X. Ying et al. **CVPR, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/pdf/2304.01484.pdf) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/XinyiYing/LESPS)

- **RDIAN**, Receptive-Field and Direction Induced Attention Network for Infrared Dim Small Target Detection With a Large-Scale Dataset IRDST.
  - H. Sun, J. Bai, F. Yang and X. Bai. **TGRS, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10011452) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/sun11999/RDIAN)

- Monte Carlo Linear Clustering with Single-Point Supervision is Enough for Infrared Small Target Detection
  - B. Li et al.  **ICCV, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content/ICCV2023/html/Li_Monte_Carlo_Linear_Clustering_with_Single-Point_Supervision_is_Enough_for_ICCV_2023_paper.html) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/YeRen123455/SIRST-Single-Point-Supervision)


- **MSHNet**: Infrared Small Target Detection with Scale and Location Sensitivity.
  - Q. Liu, et al. **CVPR, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2403.19366) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/Lliu666/MSHNet)


- **SCTransNet**: Spatial-channel Cross Transformer Network for Infrared Small Target Detection.
  - S. Yuan, et al. **TGRS, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10486932) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/xdFai/SCTransNet)

- **MiM-ISTD**: Mamba-in-Mamba for Efficient Infrared Small-Target Detection.
  - T. Chen, et al. **TGRS, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10740056) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/txchen-USTC/MiM-ISTD)


- **IRSAM**: Advancing segment anything model for infrared small target detection.
  - M. Zhang, et al. **ECCV, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/pdf/2407.07520) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/IPIC-Lab/IRSAM)

- **SeRankDet**: Pick of the Bunch: Detecting Infrared Small Targets Beyond Hit-Miss Trade-Offs via Selective Rank-Aware Attention.
  - Y. Dai, et al. **TGRS, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/10677425) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/GrokCV/SeRankDet)


### [Multi-Frame](#table-of-contents)

- A Spatial-Temporal Feature-Based Detection Framework for Infrared Dim Small Target.
  - J. Du et al. **TGRS, 2022**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10011452)

- **STDMANet**: Spatio-Temporal Differential Multiscale Attention Network for Small Moving Infrared Target Detection.
  - P. Yan, R. Hou, X. Duan, C. Yue, X. Wang, and X. Cao. **TGRS, 2023**
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10034772)


- **DTUM**: Direction-Coded Temporal U-Shape Module for Multiframe Infrared Small Target Detection.
  - R. Li et al. **TNNLS, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10321723) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/TinaLRJ/Multi-frame-infrared-small-target-detection-DTUM)


- **SSTNet**: Sliced Spatio-Temporal Network With Cross-Slice ConvLSTM for Moving Infrared Dim-Small Target Detection.
  - S. Chen, L. Ji, J. Zhu, M. Ye, and X. Yao.  **TGRS, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10381806) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/UESTC-nnLab/SSTNet)


- **DMIST**: Toward Dense Moving Infrared Small Target Detection: New Datasets and Baseline.
  - S. Chen, et al.  **TGRS, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10636251) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/UESTC-nnLab/DMIST)


- **Tridos**: Triple-domain Feature Learning with Frequency-aware Memory Enhancement for Moving Infrared Small Target Detection.
  - W. Duan, et al.  **TGRS, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10636251) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/UESTC-nnLab/Tridos)



- **LMAFormer**: Local Motion Aware Transformer for Small Moving Infrared Target Detection.
  - Y. Huang, X. Zhi, J. Hu, et al. **TGRS, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10758760) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/lifier/LMAFormer)


## [Deep Unfolding-Based Methods](#table-of-contents)

- **RPCANet**: Deep Unfolding RPCA Based Infrared Small Target Detection.
  - F. Wu, T. Zhang, L. Li, Y. Huang, and Z. Peng. **WACV, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content/WACV2024/html/Wu_RPCANet_Deep_Unfolding_RPCA_Based_Infrared_Small_Target_Detection_WACV_2024_paper.html) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/fengyiwu98/RPCANet)


## [Datasets](#table-of-contents)

### [Datasets: Single-Frame](#table-of-contents)

- **MDFA**: Miss detection vs. false alarm: Adversarial learning for small object segmentation in infrared images.
  - Wang H, Zhou L, Wang L. **ICCV, 2019**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content_ICCV_2019/html/Wang_Miss_Detection_vs._False_Alarm_Adversarial_Learning_for_Small_Object_ICCV_2019_paper.html) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/wanghuanphd/MDvsFA_cGAN)

- **SIRST**: Asymmetric contextual modulation for infrared small target detection.
  - Dai Y, Wu Y, Zhou F, et al. **WACV, 2021**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content/WACV2021/html/Dai_Asymmetric_Contextual_Modulation_for_Infrared_Small_Target_Detection_WACV_2021_paper.html) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/YimianDai/sirst)


- **SIRST-Aug**: Attention-Guided Pyramid Context Networks for Infrared Small Target Detection.
  - Tianfang Zhang, Lei Li, Siying Cao, Tian Pu, Zhenming Peng. **TAES, 2023**
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2111.03580) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/Tianfang-Zhang/AGPCNet)

- **NUDT-SIRST**: Dense Nested Attention Network for Infrared Small Target Detection.
  - B. Li, C. Xiao, L. Wang, Y. Wang, Z. Lin, M. Li, et al. **TIP, 2022**
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/iel7/83/4358840/09864119.pdf) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/YeRen123455/Infrared-Small-Target-Detection)

- **IRSTD-1k**: Shape matters for infrared small target detection.
  - M. Zhang, R. Zhang, Y. Yang et al. **CVPR, 2022**
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_ISNet_Shape_Matters_for_Infrared_Small_Target_Detection_CVPR_2022_paper.pdf) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/RuiZhang97/ISNet)

- **SIRST v2**: One-Stage Cascade Refinement Networks for Infrared Small Target Detection,
  - Y. Dai, X. Li, F. Zhou, et al. **TGRS, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10038696/) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/YimianDai/open-sirst-v2)

- **NUDT-SIRST-Sea**: MTU-Net: Multilevel TransUNet for Space-Based Infrared Tiny Ship Detection, 
  - T. Wu, B. Li, Y. Luo, et al. **TGRS, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10011449) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/TianhaoWu16/Multi-level-TransUNet-for-Space-based-Infrared-Tiny-ship-Detection)

- **DenseSIRST**: Background Semantics Matter: Cross-Task Feature Exchange Network for Clustered Infrared Small Target Detection With Sky-Annotated Dataset
  - Y. Dai, X. Meng, Q. Dai, et al. **Preprint, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2407.200782) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/GrokCV/DenseSIRST)


### [Datasets: Multi-Frame](#table-of-contents)
- A dataset for infrared detection and tracking of dim-small aircraft targets under ground / air background,
  - B. Hui, et al. **China Scientific Data, 2020**.
  - [![](https://img.shields.io/badge/Link-Dataset-green)](http://www.csdata.org/en/p/387/)

- A dataset for infrared time-sensitive target detection and tracking for air-ground application,
  - R. Fu, et al. **China Scientific Data, 2021**.
  - [![](https://img.shields.io/badge/Link-Dataset-green)](http://csdata.org/en/p/673/)

- **SAITD**: A dataset for small infrared moving target detection under clutter background,
  - X. Sun, et al. **China Scientific Data, 2021**.
  - [![](https://img.shields.io/badge/Link-Dataset-green)](http://csdata.org/en/p/553/)

- **IRDST**: Receptive-field and Direction Induced Attention Network for Infrared Dim Small Target Detection with a Large-scale Dataset IRDST.
  - H. Sun, J. Bai, F. Yang, et al. **TGRS, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2407.200782) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/sun11999/RDIAN)

- **NUDT-MIRSDT**: Direction-Coded Temporal U-Shape Module for Multiframe Infrared Small Target Detection.
  - R. Li et al. **TNNLS, 2023**
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10321723) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/TinaLRJ/Multi-frame-infrared-small-target-detection-DTUM)


- **SIRSTD**: Spatial-Temporal Transformer for Infrared Small Target Detection in Sequential Images.
  - X. Tong et al. **TGRS, 2024**
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10409231)[![](https://img.shields.io/badge/Link-Dataset-green)](https://github.com/aurora-sea/SIRSTD)


- **TSIRMT**: LMAFormer: Local Motion Aware Transformer for Small Moving Infrared Target Detection,
  - Y. Huang, X. Zhi, J. Hu, et al. **TGRS, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/document/10758760) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/lifier/LMAFormer)
  
- **IRSatVideo-LEO**: Infrared Small Target Detection in Satellite Videos: A New Dataset and A Novel Recurrent Feature Refinement Framework,
  - X. Ying, et al. **Preprint, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2409.12448) [![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/XinyiYing/RFR)


## [Recommended Benchmarks](#table-of-contents)
| Title  |  Date  | Link |
|:------|:------:|:------:|
|ISTD Python|2021|https://github.com/Tianfang-Zhang/ISTD-python|
|BasicIRSTD|2023|https://github.com/XinyiYing/BasicIRSTD|
|ISTD-Benchmark|2023|https://github.com/Linaom1214/ISTD-Benchmark|
|STD-EvalKit|2024|https://github.com/IRSTD/STD-EvalKit|

## [Recommended Surveys](#table-of-contents)
- Single-Frame Infrared Small-Target Detection: A survey.
  - M. Zhao, et al. **GRSM, 2022**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/9714770)
- Infrared small target segmentation networks: A survey.
  - R. Kou, et al. **PR, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.sciencedirect.com/science/article/pii/S0031320323004867)[![](https://img.shields.io/badge/Code-Python-orange)](https://github.com/kourenke/Review-Infrared-small-target-segmentation-networks)


# Acknowledgement
This repository was founded by [Tianfang-Zhang](https://github.com/Tianfang-Zhang), and is currently updated by [fengyiwu98](https://github.com/fengyiwu98). If you have any issue, please contact us.


-----
Note:

- ![](https://img.shields.io/badge/Code-PyTorch-orange) represents offical code.
- ![](https://img.shields.io/badge/Code-PyTorch-green) represents reproduced code.
