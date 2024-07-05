# Data Release: Flowcell_222WKJLT1

## Overview

This repository contains the ATAC-seq data and the subsequent analysis outputs for the Flowcell_222WKJLT1. The data includes raw fastq files, summary statistics, and quality control (QC) plots from the Cellranger and ArchR pipelines.

## Folder Structure

### ATAC-seq Data Folder
- Contains the raw ATAC-seq fastq files.

### Output Directory
- **Summary and Quality Control Outputs**: Includes summary plots and statistics from the Cellranger pipeline, as well as downstream QC plots using the ArchR pipeline and ARCH-BROWSER.

## Processing Details

### Cellranger Pipeline
- Used to process the ATAC-seq data.
- Output includes a summary report.
- **Key File**: `OUTPUT/CELLRANGER/summary.pdf`
- **Key File**: `OUTPUT/CELLRANGER/summary_data.xlsx`

### ArchR Pipeline
- Utilized for downstream quality control (QC) analysis, including metrics such as doublet statistics, transcription start site (TSS) enrichment, and cluster heatmaps.
- Analysis conducted using the scATACpipe, a comprehensive bioinformatics pipeline for single-cell ATAC-seq (scATAC-seq) data analysis, run with default settings.
- The pipeline includes doublet filtering using ArchR's built-in method or AMULET.
- Data processed for both peripheral blood mononuclear cells (PBMC) and bone marrow (BM) samples.
- **Key Files**:
  - `OUTPUT/ARCHR/BM_archr/multiqc_report.html`
  - `OUTPUT/ARCHR/PBMC_archr/multiqc_report.html`

## Additional Information

### Code and 
