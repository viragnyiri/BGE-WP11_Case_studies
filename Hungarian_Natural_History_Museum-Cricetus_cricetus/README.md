# Population genomic study on the Central-Eastern European populations of the critically endangered Common Hamster (Cricetus cricetus)
This repository includes all the scripts used to process RAD and low-coverage WGS reads for population genomic analyses.
This is the bioinformatic pipeline we run to produce filtered vcf files for downstream analyses from raw reads. The steps include: (1.) demultiplexing, (2.) quality and sequence filtering, (3.) mapping to the reference, (4.) variant calling, (5.) basic filtering of vcf (imiss, meanDP, maf, biallelic, lmiss), (6.) LD pruning and keeping only SNPs. The vcf produced after step (5.) is suitable for phylogenetic tree reconstruction, the vcf produced after the last step is suitable for population genomics.

# Authors 
Gábor Sramkó, University of Debrecen, Evolutionary Genomics Research Group, Hungary

# Acknowledgements
This work was supported by Cibio under the Biodiversity Genomics Europe project.



