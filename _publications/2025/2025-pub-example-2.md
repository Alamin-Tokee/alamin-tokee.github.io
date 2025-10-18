---
title:          "Transcriptomic Analysis and Predictive Modeling of Lung Squamous Cell Carcinoma"
date:           2025-09-12 00:01:00 +0800
selected:       true
#pub:            "Biological Material and Devices"
pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  Lung Squamous Cell Carcinoma (LUSC) is a prevalent and aggressive form of lung cancer with a significant impact on global health. Accurate identification and molecular characterization are crucial for improved diagnosis and therapeutic strategies. 
#   This study leverages gene expression data from The Cancer Genome Atlas (TCGA) to identify molecular signatures of LUSC. We performed differential gene expression analysis on 56907 transcripts from normal and tumor LUSC samples using an independent samples T-test with False Discovery Rate (FDR) correction. This analysis identified 4789 statistically significant differentially expressed genes (DEGs) with an adjusted p-value <= 0.01 and absolute log2 fold change >= 2. Subsequent gene set enrichment analysis using the MSigDB Hallmark gene sets revealed significant enrichment in pathways related to E2F Targets and G2-M Checkpoint. To assess the predictive power of these findings, we selected the top 50 DEGs by absolute log2 fold change and trained several machine learning models. The CatBoost classifier achieved the highest accuracy of 99.1% on an independent test set. These results demonstrate that a focused set of differentially expressed genes can effectively distinguish between normal and tumor LUSC samples, highlighting their potential as biomarkers for LUSC diagnosis and providing insights into the underlying biological mechanisms.
cover:          /assets/images/covers/gene2.png
authors:
  - Md Al Amin*
  - Mahjebin Jerin
  - Mehedi Hasan
  - Bikash Kumar Paul
  - Touhid Bhuiyan
links:
  Code: https://github.com/luost26/academic-homepage
  Paper: https://www.biorxiv.org
---
