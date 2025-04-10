# ChIP-Seq Using R
 
# ChIP-Sequencing of Histone H3 using R

This repository presents a project on **ChIP-Sequencing of Histone H3**, focusing on genome-wide profiling of histone modifications using R. The analysis leverages
Bioconductor tools to perform peak annotation, visualization, and functional enrichment analysis.

## Overview

Chromatin Immunoprecipitation followed by sequencing (ChIP-Seq) is a powerful technique to study protein-DNA interactions and understand epigenetic regulation.
This project uses R-based tools to map histone H3 binding sites and explore associated biological functions.

## Objectives

Identify genome-wide histone H3 binding sites
Annotate genomic features of peak regions
Perform pathway and gene ontology enrichment analysis

## Tools & Technologies

**R Programming Language**
**ChIPseeker** : Peak annotation and visualization
**ReactomePA** : Functional enrichment analysis
**Bioconductor packages** : Data handling and visualization

## 🧪 Workflow Summary

1. **Data Acquisition**  
   BED files downloaded from SRA (GSM accessions)
2. **Peak Annotation**  
   Annotate genomic features (TSS, exon, intron, etc.) using `annotatePeak`
   Visualize annotations with pie and bar plots
3. **ChIP Profiling**  
   Generate coverage plots and heatmaps of peak regions
   Profile peak binding around TSS and genebody regions
4. **Functional Enrichment Analysis**  
   Use `ReactomePA` to explore enriched pathways and biological processes

## Results

Genome-wide distribution plots
Heatmaps of peak enrichment
Functional enrichment charts (Gene Ontology, KEGG, Reactome)
Genomic annotation pie/bar/venn diagrams

## References

Yu, G. et al. (2015) *ChIPseeker: an R/Bioconductor package for ChIP peak annotation, comparison and visualization.*
Nakato, R. (2021) *Practical workflow for ChIP-seq analysis.*
Park, P. J. (2009) *ChIP-seq: advantages and challenges of a maturing technology.*

## Contributors

**Shivani Nanvandar**  
**Preenon Bagchi**  

---
