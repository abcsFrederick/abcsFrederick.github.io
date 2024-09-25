---
hide:
  - navigation
  - toc
---


* [ASCENT](https://github.com/abcsFrederick/ASCENT)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - ASE (alternate splicing events) are identified and quantified using the ASCENT (**A**lternate **S**pli**C**ing **E**veNt **T**ools) pipeline. This workflow can be used for multi-group multi-contrasts scenarios.
* [ASPEN](https://github.com/abcsFrederick/ASAP)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - ASPEN or **A**tac **S**eq **P**ip**E**li**N**e is CCBR's pipeline to calls peaks for ATAC-Seq datasets. It currently accepts paired-end Illumina data and calls peak using MACS2 and Genrich peak callers.
* [CARLISLE](https://github.com/abcsFrederick/CARLISLE) ![snakemake](images/snakemake-small.svg)
    - **C**ut **A**nd **R**un ana**L**ys**IS** pipeLin**E** calls peaks using MACS2, SEACR and GoPeaks on spike-in normalized input fastqs.
* [CCBR_circRNA_AmpliconSeq](https://github.com/abcsFrederick/CCBR_circRNA_AmpliconSeq)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - This is a snakemake workflow to process circRNA AmpliconSeq datasets generated to study circRNAs in KSHV and human hosts using divergent primers.
* [CHAMPAGNE](https://github.com/abcsFrederick/CHAMPAGNE)&nbsp;&nbsp;&nbsp;&nbsp;![nextflow](images/nextflow-small.svg)
    - **CH**rom**A**tin i**M**muno **P**recipit**A**tion sequencin**G** a**N**alysis pip**E**line calls ChIPseq peaks using MACS2, GEM, and SICER followed by motif enrichment and other downstream analysis.
* [CHARLIE](https://github.com/abcsFrederick/CHARLIE)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - **C**ircrnas in **H**ost **A**nd vi**R**uses ana**L**ysis p**I**p**E**line detects, annotates and quantifies circRNAs in host + virus references using CIRCExplorer2, CIRI2 and many other tools in parallel.
* [CRUISE](https://github.com/abcsFrederick/CRUISE)&nbsp;&nbsp;&nbsp;&nbsp;![nextflow](images/nextflow-small.svg)
    - **C**rispr sc**R**een seq**U**encIng analy**S**is pip**E**line can be used for whole genome CRISPR KO analysis with MaGeck, Bagel and drugZ.
* [DNAnexus](https://github.com/abcsFrederick/DNAnexus)
    - This repository provides access to a set of pipelines developed by CCBR members to analyze NGS data on DNAnexus. They allow a user to process raw data starting from FastQ files to reach common endpoints for downstream analysis such as a list of annotated mutations, a set of annotated peaks, or a raw counts matrix for differential expression analysis.
* [DTEG](https://github.com/NCI-RBL/Dockers/tree/main/workflows/DTEG)&nbsp;&nbsp;&nbsp;&nbsp;![nextflow](images/nextflow-small.svg)
    - Integration of RNA-seq and Ribo-seq to calculate translation efficiency as the number of ribosomes per gene, normalized to transcript abundance.
* [HapFerret](https://github.com/abcsFrederick/HapFerret)
    - HapFerret is an Expectation-Maximization (EM) implementation that is characterized by flexibility and ease of use, notable its use of a natural format for input genotypes and output haplotypes.
* [HERVx](https://github.com/abcsFrederick/HERVx)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - Human Endogenous Retrovirus expression pipeline, as known as HERVx, is a containerized pipeline to characterize retrotranscriptome. HERVx calculates Human Endogenous Retrovirus (HERV) expression in paired-end RNA-sequencing data.
* [ISOMIR](https://github.com/NCI-RBL/Dockers/tree/main/workflows/isomiR)&nbsp;&nbsp;&nbsp;&nbsp;![nextflow](images/nextflow-small.svg)
    - Detection and annotation of microRNA isoforms (isomiRs).
* [iCLIP](https://github.com/abcsFrederick/iCLIP_V3)&nbsp;&nbsp;&nbsp;&nbsp;![nextflow](images/nextflow-small.svg)
    - Individual-nucleotide resolution Cross-Linking and ImmunoPrecipitation (iCLIP); multi-sample peak identification and annotation analysis; differential analysis using DIFFBIND and MANORM.
* [l2p](https://github.com/abcsFrederick/l2p)
    - List-to-pathway, or l2p, is an R package for gene set enrichment analysis that is optimized for speed.
* [METRO](https://github.com/abcsFrederick/METRO)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - **M**ouse n**E**oan**T**igen p**R**edict**O**r is a pipeline to characterize the effect of a mutation on an amino acid sequences and to predict the binding of peptides to any MHC molecule using netMHCpan.
* [MAAPster](https://github.com/abcsFrederick/MAAPster)
    - MAAPster, also known as MicroArray Analysis Pipeline, is a comprehensive Shiny application and R package that performs transcriptome analysis of human or mouse Affymetrix gene expression data.
* [MNaseSeq](https://github.com/abcsFrederick/MAPLE)
    - MNase-seq Analysis PipeLinE (MAPLE): multi-sample DYAD fragment identification and quantification.
* [MOP2](https://github.com/NCI-RBL/Dockers/tree/main/workflows/MOP2)&nbsp;&nbsp;&nbsp;&nbsp;![nextflow](images/nextflow-small.svg)
    - Estimation of the length of mRNA poly-A tail from Nanopore reads using Tailfindr and Nanopolish [PubMed article link](https://pubmed.ncbi.nlm.nih.gov/36723817/)
* [RENEE](https://github.com/abcsFrederick/RENEE)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - **R**na s**E**quencing a**N**alysis pip**E**lin**E** or RENEE is an open-source, reproducible, and scalable solution for analyzing RNA-seq data. The pipeline consists of a series of data processing and quality-control steps orchestrated by Snakemake, a flexible and scalable workflow management system, to submit jobs to a cluster or cloud provider.
* [RiboFootPrint](https://github.com/NCI-RBL/Dockers/tree/main/workflows/RiboFootPrint) 
    - Detection of Ribosomal footprints from NGS data.
* [SF_ATAC-seq](https://github.com/abcsFrederick/SF_ATAC-seq)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - The ATAC-seq (Assay for Transposase-Accessible Chromatin using sequencing) pipeline typically follows several steps to analyze paired-end sequencing data and identify regions of open chromatin (peaks).
* [SF_biocontainer](https://github.com/abcsFrederick/SF_biocontainer)
    - SF_biocontainer is a github repo with the Docker file used to build containers for CCRSF pipelines.
* [SF_Fastq-QC](https://github.com/abcsFrederick/SF_Fastq-QC)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - Sequencing Facility Fastq-QC pipeline: No pipe - an abbreviated pipeline that will run Fastqc, Fastq screen and generate MultiQC report.
* [SF_LR_SOMATIC](https://github.com/abcsFrederick/SF_LR_SOMATIC)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - This pipeline processes long-read (LR) sequencing data to identify somatic mutations including single nucleotide variants (SNVs), structural variants (SVs), and copy number alterations (CNAs) using various bioinformatics tools.
* [SF_LR_Transcriptome](https://github.com/abcsFrederick/SF_LR_Transcriptome)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - Long read transcriptome pipeline for Pacbio and ONT.
* [SF_LR_VAP](https://github.com/abcsFrederick/SF_LR_VAP)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - The SF Long Read Variant Analysis Pipeline (SF_LR_VAP) is a bioinformatics workflow tailored for the comprehensive analysis of long-read sequencing data.
* [SF_MAS-SC](https://github.com/abcsFrederick/SF_MAS-SC)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - In the SF Multiplexed Arrays Sequencing (SF_MAS-SC) workflow, full-length cDNA sequences are processed and classified against a reference annotation database. This workflow identifies novel genes and isoforms, and outputs count matrices at both the gene and isoform levels.
* [SF_miRNA](https://github.com/abcsFrederick/SF_miRNA)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - This repository contains workflows/scripts for processing small RNA sequencing data. The pipeline includes steps for mapping reads to the reference genome and the miRNA database and estimating the abundance of miRNAs.
* [SF_Polylox-BC](https://github.com/abcsFrederick/SF_Polylox-BC)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - This repository contains workflows/scripts for processing Pacbio reads integrated with cell barcodes to Polylox barcodes, generating comprehensive reports and visualizations for Polylox barcode analysis.
* [SINCLAIR](https://github.com/abcsFrederick/SINCLAIR)&nbsp;&nbsp;&nbsp;&nbsp;![nextflow](images/nextflow-small.svg)
    -  **SIN**gle **C**el**L** **A**nalys**I**s **R**esource or SINCLAIR is developed by the CCR Collaborative Bioinformatics Resource as an open-source, reproducible solution for multiple single cell next-generation modalities.
* [TRANQUIL](https://github.com/abcsFrederick/TRANQUIL)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - TRANQUIL or "TRna AbundaNce QUantification pIpeLine" is a Snakemake pipeline which quantifies tRNA using the mim-tRNAseq tool.
* [LOGAN](https://github.com/abcsFrederick/LOGAN)&nbsp;&nbsp;&nbsp;&nbsp;![nextflow](images/nextflow-small.svg)
    - LOGAN is a comprehensive whole genome-sequencing pipeline following the Broad's set of best practices.
* [XAVIER](https://github.com/abcsFrederick/XAVIER)&nbsp;&nbsp;&nbsp;&nbsp;![snakemake](images/snakemake-small.svg)
    - e**X**ome **A**nalysis and **V**ar**I**ant explor**ER** aims to accurately call germline and somatic variants, to infer CNVs, and annotate variants.

