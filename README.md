# aa-tRNA-seq

[![DOI](https://zenodo.org/badge/888063728.svg)](https://doi.org/10.5281/zenodo.15653410)

Public-facing repo for our Nature Communications publication [White, Radakovic et al.](https://www.nature.com/articles/s41467-025-62545-9)
Previously preprint manuscript: [White, Radakovic et al.](https://www.biorxiv.org/content/10.1101/2024.11.18.623114v1)

## Code and figures found here (November 2024)

Here you will find processed data and figures for generating the plots contained within the manuscript figures, in the subdirectories:

* data - pre-processed aa-tRNA-seq and acid northern blot densitometry
* rmd - R markdown files for making the plots
* figures - png files generated from the above rmd files
* ref - alignment reference files
* src - useful scripts for extracting read metrics from POD5 data using ONT's [Remora](https://github.com/nanoporetech/remora) API

## Data availability

Raw POD5 files are available from [ENA](https://www.ebi.ac.uk/ena/browser/view/ERP173835), but the links on the page are not active. Please use the links in `ena-urls.txt` to fetch POD5s (using e.g. `wget`).

Note: while Figure 3 plots will currently render upon cloning this repository and running the markdown files in the contained R project, Figure 4 files require additional large files from Remora metrics extraction. These files are hosted on Zenodo at record [10.5281/zenodo.14194756](https://zenodo.org/records/14194756)

## Library preparation protocol

A complete protocol for the sequencing approach (including EDC-activation of the 3´ adapter for chemical ligation, and chemical ligation conditions) is available on Benchling [here](https://benchling.com/protocols/1vXce4Gw/acylated-deacylated-trna-library-preparation-for-rna004-sequencing-final).

## Analysis pipeline

A Snakemake analysis pipeline is available at <https://github.com/rnabioco/aa-tRNA-seq-pipeline>
