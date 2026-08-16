---
title:          "Longitudinal whole transcriptomic profiling of live cells through domain adaptation"
date:           2026-08-13 00:01:00 +0800
selected:       True
pub:            "bioRxiv"
# pub_pre:        "Submitted to Light: Science and Applications; "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
pub_date:       "2026"

abstract: >-
  Tracking transcriptomic profiles of cells over time in response to developmental cues and environmental stimuli can reveal critical insights into the fundamental mechanisms of development and disease. However, longitudinal molecular profiling at the global transcriptome level remains a major challenge, as RNA sequencing fundamentally alters or destroys cells. To overcome these limitations, we developed PENNE, a deep-learning framework that infers whole-transcriptomic profiles directly from live-cell images. Using gated attention mechanisms, PENNE trains on spatial transcriptomic datasets to align morphological features with gene expression. To enable inferences from images, our model performs domain adaptation to eliminate discrepancies between stained and unstained tissue images, effectively transferring molecular information from tissue sections to live-cell imaging. PENNE accurately identifies cell-type-specific and radiation-response markers via imputed expression. Furthermore, using only live-cell images stained with a G2/M cell cycle marker, our model captures temporal gene dynamics, evidenced by strong correlations between predicted expression and both ground-truth cellular confluency and cell-cycle progression. By bridging the gap between data-rich spatial transcriptomics and the practicality of live-cell imaging, PENNE provides a powerful new framework for monitoring molecular temporal dynamics directly through morphological information. This approach enables a paradigm-shifting workflow, fusing transcriptome-wide data with live-cell microscopy to fuel the discovery of novel gene programs via scalable, non-invasive, real-time interrogation of cellular states.
cover:          /assets/images/covers/penne.png
authors:
- Zhi Fei Dong
- Shreya Mishra 
- Maha Mohamed Tageldein
- Chris McIntosh
- Shane M. Harding
- Gregory W. Schwartz#
links:
  Paper: https://www.biorxiv.org/content/10.64898/2026.08.07.743564v1
  Code: https://github.com/schwartzlab-methods/penne
---
