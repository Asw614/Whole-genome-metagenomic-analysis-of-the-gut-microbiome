# Whole genome metagenomic analysis of the gut microbiome

The codes used for the whole genome sequencing analysis of the gut microbiome from the HIV infected individuals.

## Aim

The aim of the project is to establish shotgun metagenomics workflow to analyze HIV-1 infected individuals on antiretroviral therapy (ART) and HIV-1 negative healthy controls. This study was performed to identify the taxonomic profile and functional capacity of microbial community. 

## Outline
### Pre-processing
1) Removal of host DNA contamination.
2) Adapter trimming.
3) Removal of low quality reads.

### Sequence Analysis
1) Taxonomy profiling (MetaPhlAn2).
2) Functional prediction (HUManN2).
3) Gene richness Asseessment.
4) Virulence and Antimicrobial resistance gene prediction.

### Post-processing
1) Rarefaction analysis.
2) Biomarker prediction (LEfSe).
3) Statistical and Correlation analysis.

## Requirements
1. Python (version >= 3.7).
2. R packages.

Please click [here](https://github.com/biobakery/humann) for HUManN2 requirements.


```
# ggplot2==3.3.2
# phyloseq==1.30.0
# vegan==2.5.6
# reshape==0.8.8
# ggpubr==0.4.0
# psych==2.0.9
# scales==1.1.1
# gplots==3.1.0
```
