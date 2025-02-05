# Succession_functional_diversity

The manuscript is accessible on BioarXiv on this link: 

This repository contains all the necessary code to reproduce the main figures and central data/statistics

Everything necessary to generate table and figures should already by found in the "data" folder upon download

Following Lotus2 and MATAFILER processing, 16S, ITS, and shotgun metagenome sequence data have been arranged into phyloseq R-Data objects (from the "phyloseq" R package)
	- The phyloseq data represent the "initial" state of the data input into R scripts
	- Other initial data are in csv or tab-separated text files
	- Subsequent scripts proceed with the calculations and figures outlined in the methods section of the manuscript


System requirements
MacOS Sequoia 15.1 or higher
32gb RAM for reasonable processing times

Software dependencies
Rstudio (ver. 2024.12.0 "Kousa Dogwood" Release (cf37a3e5, 2024-12-11) for macOS)
R (ver. 4.4.1)
All R packages required to run the scripts are specified and loaded within each .Rmd file

All scripts have been tested on 2024-12-10 and run well. Pathways for all input files (located in the "Data" folder) need to be changed to local folders. 



# Licence
This is provided under the MIT license. See LICENSE for more information.
