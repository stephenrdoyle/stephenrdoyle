---
layout: paper
title: "MethPat: a tool for the analysis and visualisation of complex methylation patterns obtained by massively parallel sequencing"
year: "2016"
shortref: "Wong <i>et al.</i> <i>BMC Bioinformatics</i> 2016"
nickname: methpat-methylation
journal: "BMC Bioinformatics"
volume: 
issue:
pages: 
authors: "Wong NC, Pope BJ, Candiloro I, Korbie D, Trau M, Wong SQ, Mikeska T, Van Denderen BJW, Thompson EW, Eggers S, DOYLE SR, Dobrovic A"
image: 
redirect_from: 
fulltext: https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-0950-8
pdflink: 
github: http://bjpop.github.io/methpat/)
pmid: 
pmcid: 
f1000: 
doi: "10.1186/s12859-016-0950-8"
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
tags: [methpat, methylation]
---
{% include JB/setup %}

# Abstract 

**Background**
DNA methylation at a gene promoter region has the potential to regulate gene transcription. Patterns of methylation over multiple CpG sites in a region are often complex and cell type specific, with the region showing multiple allelic patterns in a sample. This complexity is commonly obscured when DNA methylation data is summarised as an average percentage value for each CpG site (or aggregated across CpG sites). True representation of methylation patterns can only be fully characterised by clonal analysis. Deep sequencing provides the ability to investigate clonal DNA methylation patterns in unprecedented detail and scale, enabling the proper characterisation of the heterogeneity of methylation patterns. However, the sheer amount and complexity of sequencing data requires new synoptic approaches to visualise the distribution of allelic patterns.

**Results**
We have developed a new analysis and visualisation software tool “Methpat”, that extracts and displays clonal DNA methylation patterns from massively parallel sequencing data aligned using Bismark. Methpat was used to analyse multiplex bisulfite amplicon sequencing on a range of CpG island targets across a panel of human cell lines and primary tissues. Methpat was able to represent the clonal diversity of epialleles analysed at specific gene promoter regions. We also used Methpat to describe epiallelic DNA methylation within the mitochondrial genome.

**Conclusions**
Methpat can summarise and visualise epiallelic DNA methylation results from targeted amplicon, massively parallel sequencing of bisulfite converted DNA in a compact and interpretable format. Unlike currently available tools, Methpat can visualise the diversity of epiallelic DNA methylation patterns in a sample.

## Data availability

The raw amplicon sequencing data, Bismark alignments and Methpat output files associated with this manuscript have been published with the DOI 10.1186/s13742-015-0098-x.

Methpat software can be obtained from this URL. (http://bjpop.github.io/methpat/)
