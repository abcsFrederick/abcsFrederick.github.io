# Advanced Biomedical Computational Science (ABCS) GitHub Repository

![ABCS Graphic](ABCS logo2022_350ppi.png)

## About Us

The [Advanced Biomedical Computational Science (ABCS)](https://frederick.cancer.gov/research/bioinformatics-and-computational-science/advanced-biomedical-computational-science) group is a part of the Bioinformatics and Computational Science (BACS) directorate at [Frederick National Laboratory for Cancer Research](https://frederick.cancer.gov/). ABCS provides bioinformatics, mathematical simulation and modeling, image analysis and visualization, nanoinformatics, proteomic analysis, data integration support for scientific projects through database maintenance and development, and scientific web application development support to the [National Cancer Institute](https://www.cancer.gov) (NCI) and [National Institutes of Health](https://www.nih.gov) (NIH) scientists and staff.

The tables below provide links and brief descriptions of ABCS GitHub repositories. Information on whether the repository handles dependencies, is modularized and/or containerized is also provided.
Repositories are categorized under "Statistics", "Imaging and Visualization", "Next-generation sequencing (NGS)", or "Other" topics.


## Statistics

| Repository Name | Description | Dependencies Handled | Modularized | Containerized |
| --- | --- | --- | --- | --- |
| [Clone Stability](https://github.com/abcsFrederick/Clone_stability) | This site contains the programs used in the publication "HIV Infected CD4+ T Cell Clones Are More Stable than Uninfected Clones During Long-Term Antiretroviral Therapy". Shuang Guo, Brian Luke, Amy R. Henry, Samuel Darko, Leah D. Brandt, Ling Su, David Sun, Daria Wells, Kevin W. Joseph, Dimiter Demirov, Elias K. Halvas, Daniel C. Douek, Xiaolin Wu, John W. Mellors, Stephen H. Hughes. PLoS Pathogens, 2022. | Yes | Yes | No |
| [Linear Regression](https://github.com/abcsFrederick/LinearRegression) | Welcome to the repository for the linear regression materials for Statistics for Lunch! | No | No | No |
| [ML-Caution](https://github.com/abcsFrederick/ML-Caution) | P-hacking and abuse of machine learning: A cautionary tale. Presented at GitHub Universe - Education Day on Nov 15, 2019. | No | No | No |



## Imaging and Visualization

| Repository Name | Description | Dependencies Handled | Modularized | Containerized |
| --- | --- | --- | --- | --- |
| [RMS-AI](https://github.com/abcsFrederick/RMS_AI) |  Github page for Predicting survival of rhabdomyosarcoma patients based on deep-learning of hematoxylin and eosin images manuscript. | Yes | Yes | No |
| [SlideSeg3](https://github.com/abcsFrederick/SlideSeg3) | SlideSeg3 is an enhanced python3 version of the original SlideSeg. Welcome to SlideSeg, a python module modified from SlideSeg that allows you to segment whole slide images into usable image chips for deep learning. Image masks for each chip are generated from associated markup and annotation files. | Yes | Yes | No |
| [Quick2Insight](https://github.com/abcsFrederick/Quick2Insight) | Coming soon! | No | No | No |



## Next-generation sequencing (NGS)

| Repository Name | Description | Dependencies Handled | Modularized | Containerized |
| --- | --- | --- | --- | --- |
| [ASAP](https://github.com/CCBR/ASAP) |  ASAP or Atac Seq Analysis Pipeline is CCBR's pipeline to calls peaks for ATACseq datasets. | Yes | Yes | No |
| [ASCENT](https://github.com/CCBR/ASCENT) | ASE (alternate splicing events) are identified and quantified using the ASCENT (Alternate SpliCing EveNt Tools) pipeline. This workflow can be used for multi-group multi-contrasts scenarios. | Yes | Yes | No |
| [CARLISLE](https://github.com/CCBR/CARLISLE) | Cut And Run anaLysIS pipeLinE (CARLISLE). | Yes | Yes | No |
| [CCBR_circRNA_AmpliconSeq](https://github.com/CCBR/CCBR_circRNA_AmpliconSeq) | This is a snakemake workflow to process circRNA AmpliconSeq datasets generated to study circRNAs in KSHV and human hosts using divergent primers. | Yes | Yes | No |
| [CHARLIE](https://github.com/CCBR/CHARLIE) | Circrnas in Host And viRuses anaLysis pIpEline. This circularRNA detection pipeline uses CIRCExplorer2, CIRI2 and many other tools in parallel to detect, quantify and annotate circRNAs. | Yes | Yes | No |
| [DNAnexus](https://github.com/CCBR/DNAnexus) | This repository provides access to a set of pipelines developed by CCBR members to analyze NGS data on DNAnexus. They allow a user to process raw data starting from FastQ files to reach common endpoints for downstream analysis such as a list of annotated mutations, a set of annotated peaks, or a raw counts matrix for differential expression analysis. | Yes | Yes | No |
| [HapFerret](https://github.com/CCBR/HapFerret) | The Expectation-Maximization (EM) algorithm for haplotype inference has been superseded for accuracy by newer programs, e.g. PHASE and SHAPEIT, but remains useful for rapid analysis. HapFerret is an EM implementation that is characterized by flexibility and ease of use, notable its use of a natural format for input genotypes and output haplotypes. | Unknown | Yes | No |
| [HERVx](https://github.com/CCBR/HERVx) | Human Endogenous Retrovirus expression pipeline, as known as HERVx, is a containerized pipeline to characterize retrotranscriptome. HERVx calculates Human Endogenous Retrovirus (HERV) expression in paired-end RNA-sequencing data. | Yes | Yes | No |
| [l2p](https://github.com/CCBR/l2p) | List-to-pathway, or l2p, is an R package for gene set enrichment analysis that is optimized for speed! | Yes | Yes | No |
| [METRO](https://github.com/CCBR/METRO) | Mouse nEoanTigen pRedictOr pipeline, as known as METRO (formerly AASAP), is a pipeline to characterize the effect of a mutation on an amino acid sequences and to predict the binding of peptides to any MHC molecule using netMHCpan. | Yes | Yes | No |
| [MicroArrayPipeline](https://github.com/CCBR/MicroArrayPipeline) | MicroArray Analysis Pipeline, also known as MAAPster, is a comprehensive Shiny application and R package that performs transcriptome analysis of human or mouse Affymetrix gene expression data. | Yes | Yes | No |
| [Pipeliner](https://github.com/CCBR/Pipeliner) | Welcome to Pipeliner - an open-source and scalable solution to NGS analysis powered by the NIH's Biowulf cluster. Pipeliner provides access to a set of best-practices NGS pipelines developed, tested, and benchmarked by experts at CCBR and NCBR. | Yes | Yes | No |
| [Pipeliner documentation](https://github.com/CCBR/pipeliner-docs) | This repository is the main source of documentation for users and developers working with or contributing to Pipeliner | N/A | N/A | N/A |
| [RENEE](https://github.com/CCBR/RENEE) | An open-source, reproducible, and scalable solution for analyzing RNA-seq data. The pipeline consists of a series of data processing and quality-control steps orchestrated by Snakemake, a flexible and scalable workflow management system, to submit jobs to a cluster or cloud provider. | Yes | Yes | Yes |
| [TRANQUIL](https://github.com/CCBR/TRANQUIL) | TRANQUIL or "TRna AbundaNce QUantification pIpeLine" is a Snakemake pipeline which quantifies tRNA using the mim-tRNAseq tool. | Yes | Yes | Yes |
| [wgs-seek](https://github.com/CCBR/wgs-seek) | Whole Genome-Sequencing Pipeline. This is the home of the pipeline, wgs-seek. Its long-term goals: to accurately call germline and somatic variants, to infer CNVs, and to boldly annotate variants like no pipeline before! | Yes | Yes | Yes |
| [XAVIER](https://github.com/CCBR/XAVIER) | eXome Analysis and Variant explorER. This is the home of the pipeline, XAVIER. Its long-term goals: to accurately call germline and somatic variants, to infer CNVs, and to boldly annotate variants like no pipeline before! | Yes | Yes | Yes |



## Other

| Repository Name | Description | Dependencies Handled | Modularized | Containerized |
| --- | --- | --- | --- | --- |
| [Non-B GFA](https://github.com/abcsFrederick/non-B_gfa) | gfa programs for Non-B site at NCI/FNLCR. gfa is a Suite of programs developed at NCI-Frederick/Frederick National Lab to find sequences associated with non-B DNA forming motifs. | No | No | No |
| [spacesavers](https://github.com/CCBR/spacesavers) | Disk space: the final frontier. This is the home of the cli, Spacesavers. Its long-term mission: to explore shared file systems, to seek duplicated files, and to boldly report disk space usage like no bot before! | Yes | Yes | No |

