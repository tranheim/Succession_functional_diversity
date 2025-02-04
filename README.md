# Succession_functional_diversity

This repository contains all the necessary code to reproduce the main figures and central data/statistics

Everything necessary to generate table and figures should already by found in the "data" folder upon download

Following Lotus2 and MATAFILER processing, 16S, ITS, and shotgun metagenome sequence data have been arranged into phyloseq R-Data objects (from the "phyloseq" R package)
	- The phyloseq data represent the "initial" state of the data input into R scripts beginning with xxxx 
	- Other initial data are in csv or tab-separated text files
	- Subsequent scripts proceed with the calculations outlined in the methods section of the manuscript
	- To save on space, the phyloseq data object, and all intermediate data products have been saved as RData files and may be easily loaded by typing load('data_name.RData') into the R console
