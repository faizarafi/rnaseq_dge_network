# rnaseq_dge_network
# RNA-Seq Analysis Pipeline (Anonymized Project)

**Note:** This repository contains an anonymized version of an RNA-seq analysis pipeline developed for an unpublished dataset, results and images have been removed.

## Overview

This notebook demonstrates the analysis steps used in an RNA-seq project involving differential expression and network analysis. Gene names and sample metadata have been anonymized to preserve confidentiality.

## 📂 Contents

- `dge_network_proj_workflow.ipynb`: Step-by-step notebook for processing a counts matrix, performing normalization and differential expression with DESeq2, and generating basic plots (e.g., PCA, venn, volcano, heatmap, upset plots). Function annotation analysis with Gene ontology terms is also conducted. Part II involved gene regulatory network analysis with dap-seq data and WCGNA.


## 🔒 Disclaimer

This notebook does not contain raw sequencing data, identifiable sample metadata, or actual gene identifiers from the original unpublished dataset.

## ⚙️ Tools Used

- RSEM, Tximport, STAR aligner
- DESeq2 (via R)
- WCGNA, Genie3

## 📦 Requirements
Bash scripts, python and R is used. 
R dependencies should be installed via Bioconductor.
