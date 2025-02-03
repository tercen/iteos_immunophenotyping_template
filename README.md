# Flow Immunophenotyping with PhenoGraph - Template

## Description

This template performs some basic preprocessing, clustering and dimension reduction steps 
on flow cytometry data.

## Steps

* Preprocessing: channel-specific logicle transformation
* Clustering using PhenoGraph
* Dimension Reduction using UMAP
* Marker enrichment score
* Cell population (cluster) proportions computation across samples
* Relevant data visualisations

## Requirements

* An FCS File or a ZIP of multiple FCS files (imported using the "Upload File" button)
* A Sample Annotation file containing at least two columns: "filename" and "Condition"

