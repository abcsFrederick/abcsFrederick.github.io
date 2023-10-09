## 🧬 Next-Generation Sequencing

* [ASAP](https://github.com/CCBR/ASAP){:target="_blank"}
    - Atac Seq Analysis Pipeline (ASAP) is CCBR's pipeline to calls peaks for ATACseq datasets.
* [ASCENT](https://github.com/CCBR/ASCENT){:target="_blank"}
    - ASE (alternate splicing events) are identified and quantified using the ASCENT (Alternate SpliCing EveNt Tools) pipeline. This workflow can be used for multi-group multi-contrasts scenarios.
* [CARLISLE](https://github.com/CCBR/CARLISLE){:target="_blank"}
    - Cut And Run anaLysIS pipeLinE (CARLISLE).
* [CCBR_circRNA_AmpliconSeq](https://github.com/CCBR/CCBR_circRNA_AmpliconSeq){:target="_blank"}
    - This is a snakemake workflow to process circRNA AmpliconSeq datasets generated to study circRNAs in KSHV and human hosts using divergent primers.
* [CHARLIE](https://github.com/CCBR/CHARLIE){:target="_blank"}
    - Circrnas in Host And viRuses anaLysis pIpEline. This circularRNA detection pipeline uses CIRCExplorer2, CIRI2 and many other tools in parallel to detect, quantify and annotate circRNAs.
* [DNAnexus](https://github.com/CCBR/DNAnexus){:target="_blank"}
    - This repository provides access to a set of pipelines developed by CCBR members to analyze NGS data on DNAnexus. They allow a user to process raw data starting from FastQ files to reach common endpoints for downstream analysis such as a list of annotated mutations, a set of annotated peaks, or a raw counts matrix for differential expression analysis.
* [HapFerret](https://github.com/CCBR/HapFerret){:target="_blank"}
    - HapFerret is an Expectation-Maximization (EM) implementation that is characterized by flexibility and ease of use, notable its use of a natural format for input genotypes and output haplotypes.
* [HERVx](https://github.com/CCBR/HERVx){:target="_blank"}
    - Human Endogenous Retrovirus expression pipeline, as known as HERVx, is a containerized pipeline to characterize retrotranscriptome. HERVx calculates Human Endogenous Retrovirus (HERV) expression in paired-end RNA-sequencing data.
* [l2p](https://github.com/CCBR/l2p){:target="_blank"}
    - List-to-pathway, or l2p, is an R package for gene set enrichment analysis that is optimized for speed.
* [METRO](https://github.com/CCBR/METRO){:target="_blank"}
    - Mouse nEoanTigen pRedictOr pipeline, as known as METRO (formerly AASAP), is a pipeline to characterize the effect of a mutation on an amino acid sequences and to predict the binding of peptides to any MHC molecule using netMHCpan.
* [MicroArrayPipeline](https://github.com/CCBR/MicroArrayPipeline){:target="_blank"}
    - MicroArray Analysis Pipeline, also known as MAAPster, is a comprehensive Shiny application and R package that performs transcriptome analysis of human or mouse Affymetrix gene expression data.
* [Pipeliner](https://github.com/CCBR/Pipeliner){:target="_blank"}
    - An open-source and scalable solution to NGS analysis powered by the NIH's Biowulf cluster. Pipeliner provides access to a set of best-practices NGS pipelines developed, tested, and benchmarked by experts at CCBR and NCBR.
* [Pipeliner documentation](https://github.com/CCBR/pipeliner-docs){:target="_blank"}
    - This repository is the main source of documentation for users and developers working with or contributing to Pipeliner.
* [RENEE](https://github.com/CCBR/RENEE){:target="_blank"} <img src="../assets/images/snakemake.jpg" width="45" height="15" />
    - An open-source, reproducible, and scalable solution for analyzing RNA-seq data. The pipeline consists of a series of data processing and quality-control steps orchestrated by Snakemake, a flexible and scalable workflow management system, to submit jobs to a cluster or cloud provider.
* [TRANQUIL](https://github.com/CCBR/TRANQUIL){:target="_blank"} <img src="../assets/images/snakemake.jpg" width="45" height="15" />
    - TRANQUIL or "TRna AbundaNce QUantification pIpeLine" is a Snakemake pipeline which quantifies tRNA using the mim-tRNAseq tool.
* [LOGAN](https://github.com/CCBR/LOGAN){:target="_blank"} <img src="../assets/images/nextflow.jpg" width="40" height="12" />
    - LOGAN is a comprehensive whole genome-sequencing pipeline following the Broad's set of best practices.
* [XAVIER](https://github.com/CCBR/XAVIER){:target="_blank"} <img src="../assets/images/snakemake.jpg" width="45" height="15" />
    - eXome Analysis and Variant explorER. Its long-term goals: to accurately call germline and somatic variants, to infer CNVs, and annotate variants.
* [MOP2](https://github.com/NCI-RBL/Dockers/tree/main/workflows/MOP2){:target="_blank"} <img src="../assets/images/nextflow.jpg" width="40" height="12" />
    - Estimation of the length of mRNA poly-A tail from Nanopore reads using Tailfindr and Nanopolish [PubMed article link](https://pubmed.ncbi.nlm.nih.gov/36723817/){:target="_blank"}
* [DTEG](https://github.com/NCI-RBL/Dockers/tree/main/workflows/DTEG){:target="_blank"} <img src="../assets/images/nextflow.jpg" width="40" height="12" />
    - Integration of RNA-seq and Ribo-seq to calculate translation efficiency as the number of ribosomes per gene, normalized to transcript abundance.
* [ISOMIR](https://github.com/NCI-RBL/Dockers/tree/main/workflows/isomiR){:target="_blank"} <img src="../assets/images/nextflow.jpg" width="40" height="12" />
    - Detection and annotation of microRNA isoforms (isomiRs).
* [RiboFootPrint](https://github.com/NCI-RBL/Dockers/tree/main/workflows/RiboFootPrint){:target="_blank"}
    - Detection of Ribosomal footprints from NGS data.