# Arcadia Metagenomics Toolkit

This repository contains code, workflows, and documentation for the Arcadia Metagenomics Toolkit. The toolkit is split into individual modules implementing Nextflow pipelines with Docker images for software integration. The toolkit currently contains workflows for genome-resolved metagenomics, specifically for obtaining metagenome-assembled genomes (MAGs) from prokaryotic, eukaryotic, and viral lineages. The following modules are currently implemented into the toolkit: 

1. assemblyPrep - Read filtering, assembly, mapping & differential coverage stats, and lineage splitting (Currently supports short-read data)
2. prokMAGs - Reconstructing, evaluating, and annotating prokaryotic MAGs 
3. eukMAGs - Reconstructing, evaluating, annotating, and refining eukaryotic MAGs
4. vMAGs - Reconstructing, evaluating, and annotating viral MAGs/phage genomes
5. MAGexplore - Relative abundance and diversity calculations


