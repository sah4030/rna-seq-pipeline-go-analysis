# RNA-Seq Analysis of Irinotecan Treatment in Cancer Cell Lines

This project analyzes RNA-seq data to investigate transcriptional responses to Irinotecan treatment in cancer cell lines. The work was completed as part of a final project for an advanced genomics course using the **ANGSD pipeline**, **DESeq2**, and **GO term enrichment tools**.

## Objectives
- Perform quality control on RNA-seq BAM files
- Identify differentially expressed genes between vehicle- and Irinotecan-treated samples
- Perform GO term enrichment to explore functional pathways impacted by treatment

## Methods Summary
- **Quality Control**: BAMQC, QoRTs
- **Read Counting & Differential Expression**: DESeq2
- **GO Enrichment**: clusterProfiler + REVIGO
- **Visualization**: TreeMaps, heatmaps, GO plots

## Repository Contents
- `Report ANGSD Final Project`: Final write-up of the project
- `Methods-ANGSD-Final-Project`: Expanded methods section with full source code
- `*.R`: R scripts for GO term enrichment analysis and visualization
- `*.txt / *.RData`: Supplementary data and results

## Tools & Languages
- R, DESeq2, clusterProfiler, REVIGO
- QoRTs, BAMQC
