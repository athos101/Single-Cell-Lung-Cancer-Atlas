# Single-Cell-Lung-Cancer-Atlas
## This project aims to build a single-cell lung atlas with emphasis in lung cancer, by building pipelines in a python environment.

The project goals:
  * Integraring several curated samples from papers
  * Processing and analysing the samples
  * Defining good markers to annotate the cell identities
  * Defining a detailed pipeline for the annotation and differential expression analysis
  * Defining a compositional analysis pipeline

The repository contains the following python notebooks:
  * 'Dataset Preparation'.ipynb - integrate and process the datasets.
  * 'Annotation Atlas'.ipynb - annotation of the 3 levels of cell identities.

Important libraries used:
  * Scanpy, for the anndata functions, from reading/writing single-cell files, plotting useful graphs, processing clusters and more.
  * scVI, to integrate data, remove doublets and calculate optimal parameters for dataset processing, as well as marker ranking, all using machine learning models.

What datasets were used:
  * Most datasets were downloaded from the Gene Expression Omnibus (GEO) under accession codes GSE136831, GSE135893, GSE131907, GSE123904, GSE130148, GSE148071, GSE127465, GSE154826, and GSE189357. Additional data were obtained from the Code Ocean platform (Bischoff et al., 2021) and from the West China Hospital cohort (Fan et al., 2025)

How to install the pipeline:
  * Create a python environment and download the libraries trough requirements.txt
