# TCGA-KIRC Multi-Omics Prognostic Biomarker Analysis

## Overview
This project integrates RNA-seq, DNA methylation, copy-number variation (CNV), and clinical/survival data from TCGA-KIRC to identify and characterize candidate prognostic biomarkers.

## Data
- RNA-seq
- DNA methylation
- GISTIC2 CNV
- Clinical and overall survival data

Data were obtained from TCGA/UCSC Xena.

## Methods
- Cross-omics sample matching and preprocessing
- Univariate and multivariable Cox regression
- FDR multiple-testing correction
- Kaplan-Meier survival analysis
- Pearson and point-biserial correlation
- Wilcoxon rank-sum test
- Bootstrap mediation analysis

## Key Findings
- GBA3 was identified as a candidate protective prognostic gene  
  (HR = 0.827, FDR = 2.65 × 10^-9).
- cg25080182 methylation was negatively correlated with GBA3 expression  
  (r = -0.613).
- GBA3 CNV deletion was negatively associated with GBA3 expression  
  (r = -0.165).

## Tools
R, TCGA, UCSC Xena, survival analysis, multi-omics integration
