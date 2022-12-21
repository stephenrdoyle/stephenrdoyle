---
layout: paper
title: "The confounding effects of high genetic diversity on the determination and interpretation of differential gene expression analysis in the parasitic nematode <i>Haemonchus contortus</i>"
year: "2019"
shortref: "Rezansoff <i>et al.</i> <i>IJP</i> 2019"
nickname: hcontortus_rnaseq_diversity_bias
journal: "International Journal for Parasitology"
volume: 49
issue: 11
pages: 847-858
authors: "Rezansoff AM, Laing R, Martinelli A, Redman E, Bartley D, Holroyd N, Devaney E, Doyle SR, Sargison ND, Cotton JA, Gilleard JS."
image: /assets/images/papers/2019-10-01-hcontortus-rnaseq-diversity-bias.png
redirect_from: 
fulltext: https://www.sciencedirect.com/science/article/pii/S002075191930205X?via%3Dihub
pdflink: 
github: 
pmid: 
pmcid: 
f1000: 
doi: "10.1016/j.ijpara.2019.05.012"
dryad_doi:
figshare_doi: 
zenodo_doi: 
altmetric_id: 
category: paper
# Note: 'published' is a Jekyll keyword and does not refer to whether the paper is published, but rather to whether this Markdown should be part of the rendered site.
published: true
preprint: true
embargo: false	
peerreview: false
review: false
tags: [hcontortus, rnaseq, resistance, bias]
---
{% include JB/setup %}

# Abstract 

Differential expression analysis between parasitic nematode strains is commonly used to implicate candidate genes in anthelmintic resistance or other biological functions. We have tested the hypothesis that the high genetic diversity of an organism such as *Haemonchus contortus* could complicate such analyses. First, we investigated the extent to which sequence polymorphism affects the reliability of differential expression analysis between the genetically divergent *H. contortus* strains MHco3(ISE), MHco4(WRS) and MHco10(CAVR). Using triplicates of 20 adult female worms from each population isolated under parallel experimental conditions, we found that high rates of sequence polymorphism in RNAseq reads were associated with lower efficiency read mapping to gene models under default TopHat2 parameters, leading to biased estimates of inter-strain differential expression. We then showed it is possible to largely compensate for this bias by optimising the read mapping single nucleotide polymorphism (SNP) allowance and filtering out genes with particularly high single nucleotide polymorphism rates. Once the sequence polymorphism biases were removed, we then assessed the genuine transcriptional diversity between the strains, finding ≥824 differentially expressed genes across all three pairwise strain comparisons. This high level of inter-strain transcriptional diversity not only suggests substantive inter-strain phenotypic variation but also highlights the difficulty in reliably associating differential expression of specific genes with phenotypic differences. To provide a practical example, we analysed two gene families of potential relevance to ivermectin drug resistance; the ABC transporters and the ligand-gated ion channels (LGICs). Over half of genes identified as differentially expressed using default TopHat2 parameters were shown to be an artifact of sequence polymorphism differences. This work illustrates the need to account for sequence polymorphism in differential expression analysis. It also demonstrates that a large number of genuine transcriptional differences can occur between *H. contortus* strains and these must be considered before associating the differential expression of specific genes with phenotypic differences between strains.

# Data Availability

