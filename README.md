# GO and KEGG Enrichment Analysis of Eucalyptus Transcriptomic Responses

## Overview

This repository contains a Python-based bioinformatics workflow for functional enrichment analysis of RNA-seq data from *Eucalyptus occidentalis* under gibberellin (GA) and paclobutrazol (PAC) treatments.

## Analysis Workflow

- Identification and filtering of differentially expressed genes (DEGs)
- Gene Ontology (GO) enrichment analysis across Biological Process, Molecular Function, and Cellular Component
- KEGG pathway enrichment analysis
- Multiple-testing correction using the Benjamini–Hochberg method
- Comparison of treatment-specific and shared transcriptional responses
- Visualization of significant functional terms and pathways
- Gene-level investigation of selected biological pathways

## Treatment Comparisons

- GA vs. Control
- PAC vs. Control
- GA vs. PAC

## Statistical Methods

GO enrichment is evaluated using Fisher's exact test with Benjamini–Hochberg FDR correction. Functional terms are generally considered significant at FDR < 0.05.

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook, and biological annotation resources.

## Research Context

This work contributes to the functional interpretation of transcriptomic changes associated with gibberellin signaling and growth regulation in *Eucalyptus occidentalis*.

## Reproducibility

Analysis notebooks, environment requirements, annotation references, and applicable data-access instructions will be provided as the repository is organized.
