# aa-tRNA-seq
Public-facing repo for the preprint [White, Radakovic et al.](https://www.biorxiv.org/content/10.1101/2024.11.18.623114v1)

## Code and figures found here (November 2024)
Here you will find processed data and figures for generating the plots contained within the manuscript figures, in the subdirectories:
* data - pre-processed aa-tRNA-seq and acid northern blot densitometry
* rmd - R markdown files for making the plots
* figures - png files generated from the above rmd files
* ref - alignment reference files
* src - useful scripts for extracting read metrics from POD5 data using ONT's [Remora](https://github.com/nanoporetech/remora) API

## Data availability
Complete sequencing data (including POD5 and FASTQ files) and classification models will be available at the NCBI Gene Expression Omnibus and Zenodo upon manuscript acceptance. 

## Library preparation protocol
A complete protocol for the sequencing approach (including EDC-activation of the 3´ adapter for chemical ligation, and chemical ligation conditions) is available on Benchling [here](https://benchling.com/protocols/1vXce4Gw/acylated-deacylated-trna-library-preparation-for-rna004-sequencing-final).

Note: while Figure 3 plots will currently render upon cloning this repository and running the markdown files in the contained R project, Figure 4 files require additional large files from Remora metrics extraction. We intend to host these files on Zenodo (link to full dataset forthcoming).
