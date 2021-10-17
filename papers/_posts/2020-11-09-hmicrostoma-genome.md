---
layout: paper
title: "Complete representation of a tapeworm genome reveals chromosomes capped by centromeres, necessitating a dual role in segregation and protection"
year: "2020"
shortref: "Olson <i>et al.</i> <i>BMC Biology</i> 2020"
nickname: hmicrostoma_genome
journal: "BMC Biology"
volume: 
issue:
pages: 
authors: "Olson PD, Tracey A, Bailie A, James K, Rodgers FH, DOYLE SR, Buddenborg S, Holroyd N, Berriman M"
image: 
redirect_from: 
fulltext: https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-020-00899-w
pdflink: 
github:
pmid: 
pmcid: 
f1000: 
doi: "10.1186/s12915-020-00899-w"
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
tags: [hmicrostoma, genome, assembly, annotation]
---
{% include JB/setup %}

# Abstract 

**Background**
Chromosome-level assemblies are indispensable for accurate gene prediction, synteny assessment, and understanding higher-order genome architecture. Reference and draft genomes of key helminth species have been published, but little is yet known about the biology of their chromosomes. Here, we present the complete genome of the tapeworm *Hymenolepis microstoma*, providing a reference quality, end-to-end assembly that represents the first fully assembled genome of a spiralian/lophotrochozoan, revealing new insights into chromosome evolution.

**Results**
Long-read sequencing and optical mapping data were added to previous short-read data enabling complete re-assembly into six chromosomes, consistent with karyology. Small genome size (169 Mb) and lack of haploid variation (1 SNP/3.2 Mb) contributed to exceptionally high contiguity with only 85 gaps remaining in regions of low complexity sequence. Resolution of repeat regions reveals novel gene expansions, micro-exon genes, and spliced leader trans-splicing, and illuminates the landscape of transposable elements, explaining observed length differences in sister chromatids. Syntenic comparison with other parasitic flatworms shows conserved ancestral linkage groups indicating that the *H. microstoma* karyotype evolved through fusion events. Strikingly, the assembly reveals that the chromosomes terminate in centromeric arrays, indicating that these motifs play a role not only in segregation, but also in protecting the linear integrity and full lengths of chromosomes.

**Conclusions**
Despite strong conservation of canonical telomeres, our results show that they can be substituted by more complex, species-specific sequences, as represented by centromeres. The assembly provides a robust platform for investigations that require complete genome representation.

## Data availability

The datasets generated and analysed during the current study are available in the European Nucleotide Archive (www.ebi.ac.uk/ena) under the following accessions: genome assembly GCA_000469805.3, long-read sequence data study accession PRJEB2107.

The following publicly available RNA-seq datasets were used to identify splice leader sequences: ERR337939 [69], ERR337946 [70], ERR337951 [71], ERR337958 [72], ERR337962, and ERR337963 [73] for *E. multilocularis*; ERR022872 [74], ERR022877, ERR022878 [75], ERR022880–ERR022882 [76], ERR1674583–ERR1674585 [77], ERR1674590–ERR1674592 [78], ERR506076 [79], ERR506082–ERR506084 [80], ERR506088 [81], and ERR506090 [82] for *S. mansoni*; and ERR225719-ERR225730 [83], ERR337928 [84], ERR337940 [85], ERR337952 [86], ERR337964 [87], and ERR337976 [88] for *H. microstoma*.

Code for identifying genomic splice leader loci by aligning SL sequences against the genome using BLAST is available at https://github.com/fayerodgers/trans_splicing.
