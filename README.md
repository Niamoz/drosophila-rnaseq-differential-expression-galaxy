# Drosophila RNA-seq Differential Expression Analysis with Galaxy

## Project Overview

This project documents a reference-based RNA-seq analysis workflow performed in the Galaxy platform using tutorial-provided Drosophila datasets.

The analysis follows a Galaxy Training Network workflow and includes quality control, read mapping, gene-level quantification, differential expression analysis, and functional interpretation of gene expression changes.

---

## Objective

The main goals of this project were to:

- Evaluate RNA-seq data quality.
- Align sequencing reads to a reference genome.
- Quantify gene-level expression.
- Compare treated and untreated samples.
- Identify differentially expressed genes.
- Visualize sample relationships and expression patterns.
- Perform functional enrichment analysis.

---

## Data and Training Source

The analysis was completed by following a Galaxy Training Network tutorial using tutorial-provided datasets.

The dataset includes multiple Drosophila samples, including treated and untreated groups.

The analysis outputs in this repository contain gene identifiers in the `FBgn` format, which correspond to Drosophila gene identifiers.

---

## Analysis Workflow

The workflow included the following main stages:

1. Quality control of RNA-seq reads.
2. Read alignment to the reference genome.
3. Gene-level read counting.
4. Differential expression analysis.
5. Visualization of sample relationships.
6. Heatmap generation for gene expression patterns.
7. Functional enrichment analysis.

---

## Differential Expression Analysis

Differential expression analysis was used to identify genes showing expression differences between experimental groups.

The analysis produced outputs including:

- Principal component analysis (PCA)
- Sample-to-sample distance visualization
- Differential expression heatmaps
- Gene-level expression comparisons

These outputs help assess both biological differences between groups and consistency among samples.

---

## Functional Interpretation

Functional enrichment analysis was performed to investigate the biological meaning of the differentially expressed genes.

The saved results include outputs related to:

- Gene Ontology (GO) enrichment
- KEGG pathway analysis

These analyses help identify biological processes and pathways associated with the observed expression changes.

---

## Repository Contents

```text
drosophila-rnaseq-differential-expression-galaxy/
│
├── README.md
├── PLAN.pdf
└── Galaxy20-[heatmap2_on_data_18].pdf

          
