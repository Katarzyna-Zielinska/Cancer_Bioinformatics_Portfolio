# Cancer Bioinformatics Portfolio

![Bioinformatics](https://img.shields.io/badge/Bioinformatics-Portfolio-blueviolet)
![NGS](https://img.shields.io/badge/NGS-Analysis-blue)
![RNA-seq](https://img.shields.io/badge/RNA--seq-Transcriptomics-purple)
![scRNA-seq](https://img.shields.io/badge/scRNA--seq-Single--Cell-orange)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Cancer%20Genomics-red)
![Python](https://img.shields.io/badge/Python-Data%20Analysis-yellow?logo=python)
![R](https://img.shields.io/badge/R-Bioinformatics-276DC3?logo=r)
![Snakemake](https://img.shields.io/badge/Snakemake-Workflow%20Automation-green?logo=snakemake)
![Linux](https://img.shields.io/badge/Linux-WSL2-black?logo=linux)
![GitHub](https://img.shields.io/badge/Git-GitHub-181717?logo=github)
![Status](https://img.shields.io/badge/Projects-5-brightgreen)


A collection of practical bioinformatics projects demonstrating experience in **NGS data analysis, RNA-seq, single-cell RNA-seq, machine learning, and reproducible workflow automation**.

The portfolio combines programming, statistical analysis, biological interpretation, and computational workflow development using **Python, R, Linux and modern bioinformatics tools**.

---

## Portfolio Projects

### 01 - NGS Pipeline with Python

**Focus:** NGS data quality control and preprocessing

This project demonstrates a reproducible NGS preprocessing workflow, including sequencing read quality assessment and adapter/quality trimming.

**Technologies:**
- Python
- FastQC
- fastp
- NumPy
- Linux

**Repository:**  
[01_NGS_Pipeline_Python](https://github.com/Katarzyna-Zielinska/01_NGS_Pipeline_Python)

---

### 02 - Bulk RNA-seq: Glioblastoma Differential Expression

**Focus:** Bulk RNA-seq differential expression analysis

This project analyzes gene-expression differences between glioblastoma and healthy brain tissue using a public RNA-seq dataset and statistical differential expression methods.

**Technologies:**
- R
- DESeq2
- GEOquery
- EnhancedVolcano
- pheatmap
- Bioconductor

**Repository:**  
[02_Bulk_RNAseq_Glioblastoma_DESeq2](https://github.com/Katarzyna-Zielinska/02_Bulk_RNAseq_Glioblastoma_DESeq2)

---

### 03 - Single-Cell RNA-seq: Glioblastoma

**Focus:** Single-cell RNA-seq analysis and cellular heterogeneity

This project applies single-cell RNA-seq analysis to investigate cellular populations and transcriptional heterogeneity in glioblastoma.

**Technologies:**
- R
- Seurat
- PCA
- UMAP
- Clustering
- Single-cell RNA-seq

**Repository:**  
[03_SingleCell_RNAseq_Glioblastoma-Seurat](https://github.com/Katarzyna-Zielinska/03_SingleCell_RNAseq_Glioblastoma-Seurat)

---

### 04 - Machine Learning for Glioblastoma

**Focus:** Machine learning applied to cancer genomics

This project demonstrates the application of machine-learning methods to biological and cancer-related data, including data preprocessing, model development and evaluation.

**Technologies:**
- Python
- pandas
- NumPy
- scikit-learn
- Machine Learning

**Repository:**  
[04_Machine_Learning_GBM](https://github.com/Katarzyna-Zielinska/04_Machine_Learning_GBM)

---

### 05 - RNA-seq Workflow Automation with Snakemake

**Focus:** Reproducible workflow automation and RNA-seq alignment

This project develops a dependency-aware RNA-seq alignment workflow using Snakemake, HISAT2 and SAMtools.

The workflow aligns paired-end RNA-seq reads to the human GRCh38 reference genome and produces a sorted and indexed BAM file.

The completed workflow achieved:

- **98.34% overall alignment rate**
- **96.27% properly paired reads**
- Validated BAM integrity using `samtools quickcheck`
- Successful Snakemake completion and reproducibility check

**Technologies:**
- Snakemake
- HISAT2
- SAMtools
- GRCh38
- Linux / WSL2
- Graphviz

**Repository:**  
[05_Workflow_Automation_Snakemake](https://github.com/Katarzyna-Zielinska/05_Workflow_Automation_Snakemake)

---

## Skills

### Bioinformatics

- NGS data analysis
- RNA-seq
- Bulk RNA-seq
- Single-cell RNA-seq
- Differential expression analysis
- Genome alignment
- BAM/SAM processing
- Quality control
- Reproducible bioinformatics workflows

### Programming

- Python
- R
- Linux / Bash

### Bioinformatics Tools

- FastQC
- fastp
- STAR
- STARsolo
- HISAT2
- SAMtools
- featureCounts
- MultiQC
- DESeq2
- GEOquery
- Seurat
- inferCNV
- Snakemake
- Graphviz

### Data Science & Machine Learning

- pandas
- NumPy
- scikit-learn
- Statistical analysis
- Data preprocessing
- Data visualization
- Model evaluation

### Reproducibility & Workflow Development

- Snakemake
- Git
- GitHub
- YAML configuration
- Linux command line
- WSL2
- Workflow dependency management
- Computational QC

---

# Portfolio Overview

The projects are designed as a progression from fundamental NGS processing to more advanced computational biology and workflow automation:

```text
01  NGS preprocessing
        │
        ▼
02  Bulk RNA-seq
        │
        ▼
03  Single-cell RNA-seq
        │
        ▼
04  Machine Learning
        │
        ▼
05  Workflow Automation
```

Together, the projects demonstrate the ability to work across multiple stages of a modern bioinformatics workflow:

```text
Raw sequencing data
        │
        ▼
Quality Control & Preprocessing
        │
        ▼
Genome / Transcriptome Analysis
        │
        ├── Bulk RNA-seq
        │
        └── Single-cell RNA-seq
        │
        ▼
Statistical Analysis
        │
        ▼
Machine Learning
        │
        ▼
Workflow Automation & Reproducibility
```

---

# Technical Focus

The portfolio focuses on building practical skills in:

- High-throughput sequencing data analysis
- Cancer bioinformatics
- Transcriptomics
- Single-cell genomics
- Statistical genomics
- Machine learning
- Workflow automation
- Reproducible computational research

---

# Repository Organization

Each project is maintained as a separate GitHub repository so that its code, documentation, results and workflow can be inspected independently.

```text
GitHub
│
├── Cancer-Bioinformatics-Portfolio
│
├── 01_NGS_Pipeline_Python
├── 02_Bulk_RNAseq_Glioblastoma_DESeq2
├── 03_SingleCell_RNAseq_Glioblastoma-Seurat
├── 04_Machine_Learning_GBM
└── 05_Workflow_Automation_Snakemake
```

This repository serves as the **central index and landing page** for the complete portfolio.

---

# About

This portfolio was developed to demonstrate practical computational biology and bioinformatics skills through end-to-end projects involving sequencing data, transcriptomics, cancer genomics, machine learning and reproducible workflow development.

The projects emphasize not only the use of individual tools, but also the ability to design complete computational workflows, validate results and organize analyses in a reproducible manner.

---

# Author

**Katarzyna Zielińska**

Bioinformatics Portfolio

2026
