# Kolda-Mucko-et-al.-2024_Beach-wracks
Bacterial microbiome of beach wracks revealed with V3-4 16S rRNA gene amplicon sequencing by Kolda &amp; Mucko et al. 2024.

## Beach wracks microbiome and its putative function in plastic polluted Mediterranean marine ecosystem
Anamarija Kolda(1), Maja Mucko(2)*, Ana Rapljenović(1), Zrinka Ljubešić(2), Kristina Pikelj(3), Željko Kwokal(1), Vlado Cuculić(1)

(1)Ruđer Bošković Institute, Division for Marine and Environmental Research, Zagreb, Croatia
(2)University of Zagreb, Faculty of Science, Department of Biology, Zagreb, Croatia
(3)University of Zagreb, Faculty of Science, Department of Geology, Zagreb, Croatia
*Corresponding author: maja.mucko@biol.pmf.hr

## Abstract: 
The coasts of the world's oceans and seas accumulate various types of floating debris, commonly known as beach wracks, including organic seaweeds, seagrass, and ubiquitous anthropogenic waste, mainly plastic. Beach wrack microbiome (MB), surviving in the form of a biofilm, ensures decomposition and remineralization of wracks, but can also serve as a vector of potential pathogens in the environment. Through the interdisciplinary approach and comprehensive sampling design that includes geological analysis of the sediment, plastic debris composition analysis (ATR-FTIR) and application of 16S rRNA gene metabarcoding of beach wrack MBs, this study aims to describe MB in relation to beach exposure, sediment type and plastic pollution. Major contributors in beach wrack MB were Proteobacteria, Bacteroidetes, Actinobacteria, Planctomycetes, Verrucomicrobia and Firmicutes and there was significant dissimilarity between sample groups with Vibrio, Cobetia and Planococcus shaping the “Exposed” beach sample group and Cyclobacteriaceae and Flavobacterium shaping the “Sheltered” beach sample group. Our results suggest plastisphere MB is mostly shaped by beach exposure, type of seagrass, sediment type and probably beach naturalness  with heavy influence of seawater MB and shows no significant dissimilarity between MBs from a variety of microplastics. Putative functional analysis of MB detected plastic degradation and potential human pathogen bacteria in both beach wrack and seawater MB. The research provides next crucial step in beach wrack MP accumulation research, MB composition and function investigation with focus on beach exposure as an important variable.

## Raw files 
(45 samples, paired-end reads) submmited to European Nucleotide Archive (ENA: https://www.ebi.ac.uk/ena/browser/search) under project number PRJEB53534

## Qiime2 code
Whole bioinformatic pipeline composed of steps:
1. Environment activation
2. Data import
3. Data denoise
4. Feature table generation
5. Taxonomy assignment
6. Feature table & representative sequences filtering
7. Phylogenetic tree reconstruction
8. Alpha & Beta Diversity

https://github.com/majamucko/Kolda-Mucko-et-al.-2024_Beach-wracks/blob/main/Beach_wracks%20Kolda%26Mucko%20et%20al.%202024%20QIIME2%20code.nb.html

## Analysis output visualizations
.qzv artifact visualizations of all bioinformatic pipeline steps available for viewing interactively via view.qiime2.org

https://github.com/majamucko/Kolda-Mucko-et-al.-2024_Beach-wracks/tree/main/qzv

## Metadata table
Full metadata table describing each sample, variable for their discriminations and sample groups

https://github.com/majamucko/Kolda-Mucko-et-al.-2024_Beach-wracks/blob/main/metadata_metalpath.tsv
