# viral-biogeography

This repository contains code and relevant data used to generate results and figures for the manuscript "Patterns and ecological drivers of viral communities in acid mine drainage sediments across Southern China".


## Instructions for input data and code 

Figure 1  
**vOTUs_sites.abun**: abundance of viral operational units (vOTUs) in the 90 acid mine drainage (AMD) sediments  
**PCs_sites.abun**: abundance of viral protein clusters (PCs) in the 90 AMD sediments  
**fig1c.vOTUs_PCs.culmulation_curve.R**: R scripts used to generate the culmulation curve of vOTUs and PCs  
  
Figure 2  
**biotic_abiotic.factors**: biotic and abiotic data for the 90 AMD sediment samples  
**MAGs_sites.abun**: abundance of prokaryotic populations (MAGs) in the 90 AMD sediments  
**fig2a.heatmap.R**: R scripts used to calculate the Pearson's correlations between biotic and abiotic factors  
**fig2a.mantel.R**: R scripts used to calculate the Mantel's correlations between prokaryotic, viral taxonomic and functional communities, and abiotic factors  
**fig2bc.pcoa.R**: R scripts used to generate the Principal coordinate analysis (PCoA; utilizing the Bray-Curtis dissimilarity metric) of viral taxonomic and functional structure  
**fig2de.distance_dicay.R**: R scripts used to generate distance-decay relationships (DDRs) based on Bray-Curtis similarity of viral taxonomic and functional community compositions  
  
Figure 3  
**SEM_data**: biotic and abiotic data used for structural equation modelling (SEM).  
**SEM.R**: R scripts used to perform SEM analyses  

Figure 4  
**viral_abun.by_phyla**: abundance of viruses grouped by their host phyla  
**host_abun.by_phyla**: abundance of hosts grouped by phyla  
**fig4a.R**: R scripts used to calculate virus/host abundance ratios and abundance correlations  
  
Figure 5  
**calculate_viralrange_hostrange.py**: Python scripts used to calculate the average viral ranges and host ranges by host phyla.  
**virus_host.pairs**: viral-host matches listed at the host phylum level  
**virus_host.pairs**: viral-host matches summarized at the population level  
**virus-host sub-networks for each sample.R**: R scripts used to generate virus-host subnetworks for the 90 samples  
**cal_mod_nest.matlab**: matlab scripts used to calculate modularity and nestedness for the 90 samples
