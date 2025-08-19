This repository contains an R-based (v4.3.2) pipeline for bulk RNA-seq analysis of three cancer datasets from TCGA: PAAD, COAD, LUAD. 

As PAAD did not work, I decided to pursue with a PDAC scRNA-seq analysis from two datasets merged from GEO.

Bulk RNA-seq: Data downloading, loading, processing and DESeq2 analysis (volcano plot overall, volcano plot of GOI, and violin plot of DEG from the GOI list)

scRNA-seq: Data downloading, loading, processing & QC, integration & dimensional reduction, cell type annotation, edgeR analysis (pseudobulk volcano plot, pseudobulk volcano plot of GOI, and violin plot of DEG from the GOI list by cell type)
