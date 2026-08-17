# Cancer Bioinformatics Portfolio

![Bioinformatics](https://img.shields.io/badge/Bioinformatics-Portfolio-blueviolet)
![NGS](https://img.shields.io/badge/NGS-Analysis-blue)
![RNA-seq](https://img.shields.io/badge/RNA--seq-Transcriptomics-purple)
![scRNA-seq](https://img.shields.io/badge/scRNA--seq-Single--Cell-orange)
![Cancer Genomics](https://img.shields.io/badge/Cancer%20Genomics-Glioblastoma-red)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Cancer%20Genomics-red)
![Python](https://img.shields.io/badge/Python-Data%20Analysis-yellow?logo=python)
![R](https://img.shields.io/badge/R-Bioinformatics-276DC3?logo=r)
![Snakemake](https://img.shields.io/badge/Snakemake-Workflow%20Automation-green)
![Linux](https://img.shields.io/badge/Linux-WSL2-black?logo=linux)
![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?logo=git)
![Projects](https://img.shields.io/badge/Projects-5-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

A practical bioinformatics portfolio showcasing **NGS, bulk and single-cell RNA-seq, cancer genomics, machine learning, and reproducible workflow automation**.

The portfolio combines programming, statistical analysis, biological interpretation, and computational workflow development using **Python, R, Linux, and modern bioinformatics tools**.

---

## Portfolio Projects

|   | Project | Main Focus | Technologies | Repository |
|---|---------|------------|---------------|------------|
| 01 | **NGS Pipeline – Python** | NGS preprocessing, QC, alignment and quantification | Python, FastQC, fastp, STAR, SAMtools, featureCounts, MultiQC | [View Repository](https://github.com/TWOJ_LOGIN/01_NGS_Pipeline_Python) |
| 02 | **Bulk RNA-seq – Glioblastoma** | Differential expression and functional enrichment | R, DESeq2, GEOquery, clusterProfiler | [View Repository](https://github.com/TWOJ_LOGIN/02_Bulk_RNAseq_Glioblastoma_DESeq2) |
| 03 | **Single-Cell RNA-seq – Glioblastoma** | scRNA-seq QC, clustering and cell-state analysis | R, STARsolo, Seurat, inferCNV | [View Repository](https://github.com/TWOJ_LOGIN/03_SingleCell_RNAseq_Glioblastoma-Seurat) |
| 04 | **Machine Learning – Glioblastoma** | Cancer classification using machine learning | Python, pandas, NumPy, scikit-learn | [View Repository](https://github.com/TWOJ_LOGIN/04_Machine-Learning-GBM) |
| 05 | **Workflow Automation – Snakemake** | Reproducible RNA-seq workflow automation | Snakemake, HISAT2, SAMtools, Bash, Graphviz | [View Repository](https://github.com/TWOJ_LOGIN/05_Workflow-Automation-Snakemake) |

---

### 01 - NGS / RNA-seq Pipeline with Python

**Focus:** NGS quality control, preprocessing, alignment and transcript-level quantification.

This project presents a reproducible RNA-seq processing pipeline combining quality control, read preprocessing, genome alignment and downstream quantification.

**Technologies:**
- Python
- FastQC
- fastp
- STAR
- SAMtools
- featureCounts
- MultiQC

**Repository:**  
[01_NGS_Pipeline_Python](https://github.com/Katarzyna-Zielinska/01_NGS_Pipeline_Python)

---

### 02 - Bulk RNA-seq: Glioblastoma Differential Expression

**Focus:** Bulk RNA-seq differential expression and functional enrichment analysis.

This project analyzes gene-expression differences between healthy brain tissue and glioblastoma (GBM) samples using a public GEO dataset and the DESeq2 statistical workflow.

The analysis includes differential expression, gene annotation, Gene Ontology enrichment, PCA and heatmap visualization.

**Technologies:**
- R
- Bioconductor
- DESeq2
- GEOquery
- AnnotationDbi
- org.Hs.eg.db
- clusterProfiler
- enrichplot
- ggplot2
- ggrepel
- pheatmap

**Repository:**  
[02_Bulk_RNAseq_Glioblastoma_DESeq2](https://github.com/Katarzyna-Zielinska/02_Bulk_RNAseq_Glioblastoma_DESeq2)

---

### 03 - Single-Cell RNA-seq: Glioblastoma

**Focus:** Single-cell RNA-seq processing, cellular heterogeneity and cell-state analysis.

This project processes single-cell RNA-seq data using STARsolo for alignment and gene quantification, followed by downstream analysis with Seurat.

The workflow includes quality control, dimensionality reduction, clustering, cell-type analysis and additional exploration of genomic alterations.

**Technologies:**
- STARsolo
- Seurat
- SeuratObject
- inferCNV
- FastQC
- MultiQC
- Matrix
- dplyr
- ggplot2
- pheatmap
- Bioconductor

**Repository:**  
[03_SingleCell_RNAseq_Glioblastoma-Seurat](https://github.com/Katarzyna-Zielinska/03_SingleCell_RNAseq_Glioblastoma-Seurat)

---

### 04 - Machine Learning for Glioblastoma

**Focus:** Machine learning applied to cancer-related gene-expression data.

This project applies supervised machine-learning methods to glioblastoma-related microarray data. The workflow includes data preprocessing, feature selection, model training and evaluation.

The models include **Logistic Regression** and **Random Forest**.

**Technologies:**
- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn
- PyYAML
- Logistic Regression
- Random Forest
- SelectKBest
- ANOVA F-test

**Repository:**  
[04_Machine_Learning_GBM](https://github.com/Katarzyna-Zielinska/04_Machine_Learning_GBM)

---

### 05 - RNA-seq Workflow Automation with Snakemake

**Focus:** Reproducible workflow automation and RNA-seq genome alignment.

This project develops a dependency-aware RNA-seq workflow using Snakemake, HISAT2 and SAMtools.

The workflow aligns paired-end RNA-seq reads to the human **GRCh38** reference genome and produces a coordinate-sorted and indexed BAM file.

The completed workflow achieved:

- **98.34% overall alignment rate**
- **96.27% properly paired reads**
- Validated BAM integrity using `samtools quickcheck`
- Successful Snakemake completion
- Successful final dry-run with all requested files up to date

**Technologies:**
- Snakemake
- HISAT2
- SAMtools
- FastQC
- fastp
- Graphviz
- GRCh38
- Linux / WSL2
- YAML configuration

**Repository:**  
[05_Workflow_Automation_Snakemake](https://github.com/Katarzyna-Zielinska/05_Workflow_Automation_Snakemake)

---

# Skills

## Bioinformatics

- NGS data analysis
- RNA-seq
- Bulk RNA-seq
- Single-cell RNA-seq
- Differential expression analysis
- Gene Ontology enrichment analysis
- Genome alignment
- Gene quantification
- BAM/SAM processing
- Quality control
- Reproducible bioinformatics workflows

## Programming

- Python
- R
- Linux / Bash

## Bioinformatics Tools

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
- SeuratObject
- inferCNV
- Snakemake
- Graphviz

## R / Bioconductor

- DESeq2
- GEOquery
- AnnotationDbi
- org.Hs.eg.db
- clusterProfiler
- enrichplot
- Seurat
- SeuratObject
- inferCNV
- ggplot2
- ggrepel
- pheatmap
- Matrix
- dplyr

## Data Science & Machine Learning

- pandas
- NumPy
- scikit-learn
- Statistical analysis
- Data preprocessing
- Feature selection
- Classification
- Logistic Regression
- Random Forest
- Data visualization
- Model evaluation

## Reproducibility & Workflow Development

- Snakemake
- Git
- GitHub
- YAML configuration
- Linux command line
- WSL2
- Workflow dependency management
- Computational QC

## Reference & Data Resources

- GRCh38
- GENCODE
- NCBI GEO
- Affymetrix GPL570

---

# Portfolio Overview

The projects form a progression from fundamental sequencing-data processing to transcriptomics, single-cell analysis, machine learning and workflow automation:

```text
01  NGS / RNA-seq preprocessing & alignment
                    │
                    ▼
02  Bulk RNA-seq differential expression
                    │
                    ▼
03  Single-cell RNA-seq
                    │
                    ▼
04  Machine Learning for cancer genomics
                    │
                    ▼
05  Reproducible workflow automation
```

Together, the projects cover multiple stages of a modern computational biology workflow:

```text
Sequencing / Biological Data
            │
            ▼
Quality Control & Preprocessing
            │
            ├───────────────┐
            ▼               ▼
       Bulk RNA-seq     Single-cell RNA-seq
            │               │
            ▼               ▼
 Differential Expression   Clustering /
 & Functional Analysis    Cell-state Analysis
            │               │
            └───────┬───────┘
                    ▼
             Machine Learning
                    │
                    ▼
       Workflow Automation &
          Reproducibility
```

---

# Technical Focus

The portfolio focuses on developing practical skills in:

- High-throughput sequencing data analysis
- Cancer bioinformatics
- Transcriptomics
- Bulk RNA-seq
- Single-cell RNA-seq
- Differential expression analysis
- Functional enrichment analysis
- Genome alignment and quantification
- Statistical analysis
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

The `Cancer-Bioinformatics-Portfolio` repository serves as the **central index and landing page** for the complete portfolio.

---

# About

This portfolio was developed to demonstrate practical computational biology and bioinformatics skills through end-to-end projects involving sequencing data, transcriptomics, cancer genomics, machine learning and reproducible workflow development.

The projects emphasize the ability to work with biological datasets, apply appropriate computational methods, interpret results, validate outputs and organize analyses in a reproducible manner.

---

# Author

**Katarzyna Zielińska**

Bioinformatics Portfolio

2026
