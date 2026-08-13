# ambystoma-rnaseq-analysis
# Hox11 Gene Expression During Axolotl Limb Regeneration

## Overview

This project investigated the expression of Hox11a, Hox11b and Hox11c genes during limb regeneration in *Ambystoma mexicanum* (axolotl) using RNA-seq data.

## Objectives
- Analyze Hox11a, Hox11b and Hox11c expression across different regeneration stages
- Compare their expression with other regeneration-associated genes
- Investigate potential functional and regulatory relationships

## Methods
- RNA-seq data analysis
- FASTQC - to assess sequencing data quality
- Trim-Galore - to remove adapters and low quality bases
- Kallisto - pseudoalignment and to generate transcription quantification outputs
- Differential expression analysis
- Expression comparison across regeneration time points between Hox genes and other limb regeneration associated genes such as fgfr2
- Visualization of gene expression patterns

## Results
- Transcript quantification at 0, 3, 7 and 14 dpa (days post amputation) showed that Hox11a, Hox11b and Hox11c are dynamically expressed
- Peak expression is at 7 dpa, indicating their central role in mid-regeneration
- The Pearson correlation coefficient (r) value for Hox11a and fgfr2 was found to be 0.997 ~ 1, indicating that the two genes may be co-regulated or involved in similar biological processes.
- Functional annotation associated differentially expressed genes with processes such as limb morphogenesis and pattern formation

## Tools
- Linux (WSL)
- Trim-Galore
- FASTQC
- Kallisto
- Microsoft Excel
- NCBI / Ensembl

## Project Report
The complete project report is available in `Genomics & Proteomics.pdf`.
