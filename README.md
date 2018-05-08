# FinalReport

# Join Paired Ends 
demultiplexing_join_paired_ends

Pair read1 and read2 (forward and reverse) sequencing read 


# Demultiplexing 
demultiplexing_split_libraries

Demultiplex paired reads and match to barcodes


# Closed Reference OTU Picking 
picking_OTUs_closed_reference

Sequences assigned to OTUs, clustered against the default QIIME Greengenes reference database based on 97% sequence similarity
Output will be an OTU-table that contains the number of observed OTUs and taxonomy of each sample


# Core Diversity Analyses 
core_diversity_analyses_closed, core_diversity_analyses_closed_coremicrobiome, alpha_rarefaction_closed

Combines several QIIME diversity analyses
Calculates alpha and beta diversity matrices and taxa summaries


# Compute Core Microbiome
compute_core_microbiome_closed

Filter OTU-table for OTUs present in 100% of samples
Output is a modifies OTU-table


# Heatmap 
heatmap_core_microbiome_closed

Produces heatmap of OTUs in each sample


# Compare Catagories (ADONIS)
ADONIS_closed_core_ (K/P/depth/nitrogen/ph), ADONIS_closed_ (potassium/phosphorus/depth/nitrogen/ph)

Statistical test comparing the UniFrac distance matrix between samples based on different soil characteristic categories


# Map file
map.tsv

Mapping file with metadata information of each soil sample


#Ignoreme folder
Scripts that were run as part of analysis, but was not used in final report
