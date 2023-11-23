# Flow cytometry data analysis basic template

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

* Some FCS data imported using the FCS Tercen importer
* Marker and Sample Annotation file (see https://github.com/tercen/flow_basic_annotation)

## Releases

__0.0.1__

* full workflow  

__0.0.2__

* reordered the workflow,
* added sample annotations and marker annotations
* improved performance