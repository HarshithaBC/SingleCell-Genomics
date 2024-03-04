# Single-Cell RNA-Seq Analysis

This repository contains code and documentation showcasing my practice and skills in single-cell omics analysis. The analyses cover two distinct projects -
Single Cell Analysis of PBMK 3k
Single Cell Immune Profiling of Human Ovarian Tumour 5k


Overview - 
The first analysis is the guided tutorial followed by the Seurat Documentation - https://satijalab.org/seurat/articles/pbmc3k_tutorial#setup-the-seurat-object. I learnt to analyse the dataset of Peripheral Blood Mononuclear Cells (PBMC) freely available from 10X Genomics. There are 2,700 single cells that were sequenced on the Illumina NextSeq 500. This guided tutorial introduced me to Seurat, its various functions and visualization options. The second one was an immune profiling of human ovarian tumour Isolated with a Chromium Nuclei Isolation Kit. For both the analysis, I started with the count matrix but I very strongly intend to start the analysis from the (freshly out of the sequencers) FASTA sequences. The only reason I am not able to do this is, well I graduated and hence I don't have access to the High Performing Computing and to do it locally, my laptop is really old and has extremely little memory left. The code as of now isn't fully organized but I will do that soon. Till then, you can browse around, hire me for your bioinformatics needs, give me feedback or take a moment to wonder how far humanity has come. 

Anyway, the standard workflow I followed is as follows - 

* Setting up the Seurat Object
* Pre-processing - QC, mt percentage, understand the structure of the data
* Normalizing the data
* Identification of highly variable features (feature selection)
* Scaling the data
* Perform linear dimensional reduction - PCA
* Determine the ‘dimensionality’ of the dataset
* Cluster the cells
* Running non-linear dimensional reduction -UMAP/tSNE
* Finding differentially expressed features (cluster biomarkers)
* Assigning cell type identity to clusters

## Future
I furthermore want to try different ways of normalizing the data and performing dimensional reductionality, to understand UMAP better. I also want to learn to use Seurat for multi-modal data. Another one on my bucket list is to do bacterial scRNA analysis! Having studied microbiology as one of my majors during undergrad, it would be really cool to do that. 

If you have any questions, please do not hesitate to contact me at - harshitha.chandra01@gmail.com. 

Thank you. 
