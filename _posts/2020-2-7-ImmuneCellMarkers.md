---
layout: post
title: "A Incomplete Summary of Immune Cell Markers from scRNA-Seq Literature"
---

#### [Massively parallel digital transcriptional profiling of single cells](https://www.ncbi.nlm.nih.gov/pubmed/28091601)

**Citation:** Zheng, G.X., et al. Nat Commun 2017;8:14049.

**Platform:** ~68K Human in 10X, and also bead-enriched sub-populations of PBMCs in V1 chemistry.

 Cell Type | Markers 
---|---
CD34+ cells | 
CD14+ Monocytes | 
CD19+ B cells | 
CD56+ NK cells |
CD8+ Cytotoxic T cells |
CD8+/CD45RA+ Naive Cytotoxic T cells |
Cd4+/CD45RO+ Memory T cells |
CD4+/CD45RA+/CD25- Naive T cells | 
CD4+/CD25+ Regulatory T cells | 
CD4+ Helper T |


#### [Single-cell RNA sequencing unveils the shared and the distinct cytotoxic hallmarks of human TCRVdelta1 and TCRVdelta2 gammadelta T lymphocytes.](https://pubmed.ncbi.nlm.nih.gov/31118283-single-cell-rna-sequencing-unveils-the-shared-and-the-distinct-cytotoxic-hallmarks-of-human-tcrv1-and-tcrv2-t-lymphocytes/)

**Citation:** Pizzolato, G., et al.  Proc Natl Acad Sci U S A 2019;116(24):11906-11915.

**Platform:** ~13K Human PBMC in 10x Genomics platform, including PBMC4K and PBMC8K by 3' V2 chemistry in 10X's website 

**Note:** In their analysis, CD4 and CD8 can only be seperated with a higher resolution parameter, 0.6 -> 1.2

 Cell Type | Markers 
---|---
Intermediate monocytes|CD14-, LYZ, S100A9, FCGR3A
Dendertic cells (DC) | LYZ, S100A9, FCER1A
B cells | CD79A, CD79B, CD19
Naive and central memory CD4 T cells | CD3E, CD4, SELL, CD27
Naive and central memory CD8 T cells | CD3E, CD8A, SELL, CD27
Effector memory CD4 T cells | CD3E, CD4, CD27, PRF1, GNLY
Effector memory CD8 T cells | CD3E, CD8A, CD27, PRF1, GNLY
NK | CD3E-, NKG7

#### [Seurat PBMC3K Tutorial](https://satijalab.org/seurat/v3.1/pbmc3k_tutorial.html)

**Platform:** ~3K Human PBMC in 10X platform, may be in V1 chemistry

Cell Type | Markers 
---|---
CD14+ Mono | CD14, LYZ
FCGR3A+ Mono | FCGR3A(CD16), MS4A7
DC | FCER1A, CST3
B | MS4A1(CD20)
Naive CD4+ T | IL7R(CD127), CCR7
Memory CD4+ T | IL7R(CD127), S100A4
CD8+ T | CD8A
NK | GNLY, NKG7
Platelet | PPBP

#### [Garnett Human PBMC Classifiers](https://cole-trapnell-lab.github.io/garnett/classifiers/)

**Platform:** ~100K PBMC in 10X platform, from Zheng's 2017 Nature Communication Paper.

https://www.biolegend.com/essential_markers


Cell Type | Markers 
---|---
CD34+ | CD34, THY1(CD90), ENG, KIT(CD117), PROM1(CD133)
Monocytes | CD14, FCGR1A(CD64), CD68, S100A12
Dendritic cells | IL3RA(CD123), CD1C, BATF3, THBD(CD141), CD209
B cells | CD19, MS4A1(CD20), CD79A
T cells | CD3D, CD3E, CD3G
CD4 T cells | CD4, FOXP3, IL2RA(CD25), IL7R(CD127)
CD8 T cells | CD8A, CD8B
NK cells | NCAM1(CD56), FCGR3A(CD16)




