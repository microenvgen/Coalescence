
 
## Pre-processing

The sequences from Illumina were pre-processed by removing the primers and then processed using the DADA2 pipeline ([DADA2_pipeline.Rmd]. The resulting object from this processing is dada2multithreads.Rdata (7z compressed, to decompress execute "7z x archive.7z.001").

## Contents

- metadata_Coales: The Excel file containing the necessary data.

- `Phylogenetic_tree.Rmd`: This script adds the phylogenetic tree to the phyloseq object to enable phylogenetic diversity analyses.

- `Assembly.Rmd`:This script carries out all acommunity assembly analyses.

- `ASV_vs_weight`:This script analyses the effect of specific ASVs vs weight

- `Dominance.Rmd`:This script analyses the single and pairwise coalescence experiments and reconstructs the dominance network.

- `Processing_and_statistics.Rmd`:This script carries out the initial processing and comunnity vs weight and load statistics.
 
