---
title:          "Leveraging massive H&E morphological models for phase contrast microscopy images with a generative deep learning approach"
date:           2025-09-1 00:01:00 +0800
selected:       True
# pub:            "bioRxiv"
pub_pre:        "Submitted to Light: Science and Applications; "
pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
pub_date:       "2025"

abstract: >-
  Phase contrast microscopy (PCM) is a powerful cell imaging method, and one of the few technologies to delineate and track cell structure in live cells without staining. Despite PCM’s great potential and popularity in monitoring live-cell populations, there are few algorithms to extract morphological information from these images due to the lack of large training datasets. To overcome this challenge and enable advanced, high- throughput, quantitative analysis of PCM images, we introduce SPAGHETTI (Structural Phase Adaptation via Generative Histological Enhancement and Texture-preserving Translation Integration): a lightweight image preprocessor built on a modified cycle-consistent generative adversarial network. SPAGHETTI preprocessing enables the use of large-scale deep learning models, originally trained on hematoxylin and eosin
  (H&E) pathological images that are pervasive and widespread in clinical settings, on
  PCM images through style translation. We demonstrate that using SPAGHETTI pre-
  processing achieves significantly improves performance on cell segmentation through
  the use of tissue and H&E-specific cell segmentation models. We also show that by
  passing translated PCM images across several independent datasets into H&E feature
  extractor models, we improve the performance of cell-type annotation, experimental
  media classification, and cell viability prediction. Overall, SPAGHETTI enables many
  general quantitative analyses of PCM that were previously difficult to perform due to the
  dearth of PCM-specific feature extractors, and acts as a valuable preprocessing step
  to gather new cell-state information through downstream analysis of morphological
  features.
cover:          /assets/images/covers/spaghetti.png
authors:
- Zhi Fei Dong
- Roya Navab 
- Michael Cabanero
- Irene Xie
- Ming-Sound Tsao 
- Chris McIntosh
- Gregory W. Schwartz#
links:
  Paper: https://www.biorxiv.org/content/10.1101/2025.08.27.672636v1.abstract
  Code: https://github.com/schwartzlab-methods/spaghetti
---
