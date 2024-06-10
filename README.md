# DLBCL_Tumor_Cell_States_scRNAseq

## Background
Diffuse Large B-Cell Lymphoma (DLBCL) is the most common type of non-Hodgkin lymphoma. Understanding the cellular heterogeneity within DLBCL tumors can provide insights into disease mechanisms and potential therapeutic targets. Single-cell RNA sequencing (scRNA-seq) allows for the high-resolution profiling of individual cell transcriptomes, enabling the identification of distinct cell states and subpopulations.

## Data
The scRNA-seq data used in this project is derived from DLBCL tumor samples. The dataset includes raw sequencing reads, processed gene expression matrices, and metadata for each cell.

## Project Overview
This project aims to characterize the tumor cell states and ecosystems in Diffuse Large B Cell Lymphoma (DLBCL) using single-cell RNA sequencing (scRNA-seq) data. The analysis includes cell cycle scoring, clustering, differential expression analysis, and visualization of cell states.

### Quality Control
To perform quality control on the scRNA-seq data

### Preprocessing
Preprocess the raw scRNA-seq data

### Doublet Detection
Detect and filter out doublets from the dataset

### Dimensionality Reduction
Reduce the dimensionality of the dataset for visualization and analysis

### Nearest Neighbor Graph Construction and Visualization
Construct a nearest neighbor graph and visualize the cell states

### Clustering
Cluster the cells into distinct groups

### Re-assess Quality Control and Cell Filtering
Re-assess the quality control metrics and filter cells if necessary

### Finding Marker Genes
Identify marker genes for each cluster

### Differentially Expressed Genes as Markers
Find differentially expressed genes to serve as markers

### Results
The analysis results include:
Identified cell clusters and their marker genes
Visulaising of cell states using techniques such as t-SNE and UMAP
Insights into the functional roles of different cell states within the tumor microenvironment

