# Advanced Biomedical Computational Science (ABCS) GitHub Repository

## About Us

The [Advanced Biomedical Computational Science (ABCS)](https://github.com/abcsFrederick){:target="_blank"} group is a part of the Bioinformatics and Computational Science (BACS) directorate at [Frederick National Laboratory for Cancer Research](https://frederick.cancer.gov/){:target="_blank"}. ABCS provides bioinformatics, mathematical simulation and modeling, image analysis and visualization, nanoinformatics, proteomic analysis, data integration support for scientific projects through database maintenance and development, and scientific web application development support to the [National Cancer Institute](https://www.cancer.gov){:target="_blank"} (NCI) and [National Institutes of Health](https://www.nih.gov){:target="_blank"} (NIH) scientists and staff.

The tables below provide links and brief descriptions of ABCS GitHub repositories. 📦 indicates the respective repository is containerized. Repositories are categorized under 📊 ["Statistics"](#-statistics), 🔬 ["Imaging AI"](#-imaging-ai), 🧬 ["Next-Generation Sequencing"](#-next-generation-sequencing), 🎓 ["Training"](#-training), or 📚 ["Other"](#-other) topics.

Bullet point format: 📊 ["Statistics BP"](#-statistics-bp), 🔬 ["Imaging AI BP"](#-imaging-ai-bp), 🧬 ["Next-Generation Sequencing BP"](#-next-generation-sequencing-bp), 🎓 ["Training BP"](#-training-BP), or 📚 ["Other BP"](#-other-bp), 


## 📊 Statistics 

| Repository Name | Description |
| --- | --- |
| [Clone Stability](https://github.com/abcsFrederick/Clone_stability){:target="_blank"} | This site contains the programs used in the publication "HIV Infected CD4+ T Cell Clones Are More Stable than Uninfected Clones During Long-Term Antiretroviral Therapy". Shuang Guo, Brian Luke, Amy R. Henry, Samuel Darko, Leah D. Brandt, Ling Su, David Sun, Daria Wells, Kevin W. Joseph, Dimiter Demirov, Elias K. Halvas, Daniel C. Douek, Xiaolin Wu, John W. Mellors, Stephen H. Hughes. PLoS Pathogens, 2022. [PubMed article link.](https://pubmed.ncbi.nlm.nih.gov/36044447/){:target="_blank"} |



## 🔬 Imaging AI 

| Repository Name | Description |
| --- | --- |
| [RMS-AI](https://github.com/abcsFrederick/RMS_AI){:target="_blank"} |  GitHub page for Predicting survival of rhabdomyosarcoma patients based on deep-learning of hematoxylin and eosin images manuscript. [PubMed article link.](https://pubmed.ncbi.nlm.nih.gov/36346688/){:target="_blank"} |
| [SlideSeg3](https://github.com/abcsFrederick/SlideSeg3){:target="_blank"} | SlideSeg3 is an enhanced python3 version of the original SlideSeg. |
| [Quick2Insight](https://github.com/abcsFrederick/Quick2Insight){:target="_blank"} | A framework to visualize details in volumetric datasets quickly. [Published in BioVis 2011.](https://ieeexplore.ieee.org/document/6094041){:target="_blank"} |



## 🧬 Next-Generation Sequencing 

| Repository Name | Description |
| --- | --- |
| [ASAP](https://github.com/CCBR/ASAP){:target="_blank"} |  Atac Seq Analysis Pipeline (ASAP) is CCBR's pipeline to calls peaks for ATACseq datasets. |
| [ASCENT](https://github.com/CCBR/ASCENT){:target="_blank"} | ASE (alternate splicing events) are identified and quantified using the ASCENT (Alternate SpliCing EveNt Tools) pipeline. This workflow can be used for multi-group multi-contrasts scenarios. |
| [CARLISLE](https://github.com/CCBR/CARLISLE){:target="_blank"} | Cut And Run anaLysIS pipeLinE (CARLISLE). |
| [CCBR_circRNA_AmpliconSeq](https://github.com/CCBR/CCBR_circRNA_AmpliconSeq){:target="_blank"} | This is a snakemake workflow to process circRNA AmpliconSeq datasets generated to study circRNAs in KSHV and human hosts using divergent primers. |
| [CHARLIE](https://github.com/CCBR/CHARLIE){:target="_blank"} | Circrnas in Host And viRuses anaLysis pIpEline. This circularRNA detection pipeline uses CIRCExplorer2, CIRI2 and many other tools in parallel to detect, quantify and annotate circRNAs. |
| [DNAnexus](https://github.com/CCBR/DNAnexus){:target="_blank"} | This repository provides access to a set of pipelines developed by CCBR members to analyze NGS data on DNAnexus. They allow a user to process raw data starting from FastQ files to reach common endpoints for downstream analysis such as a list of annotated mutations, a set of annotated peaks, or a raw counts matrix for differential expression analysis. |
| [HapFerret](https://github.com/CCBR/HapFerret){:target="_blank"} | HapFerret is an Expectation-Maximization (EM) implementation that is characterized by flexibility and ease of use, notable its use of a natural format for input genotypes and output haplotypes. |
| [HERVx](https://github.com/CCBR/HERVx){:target="_blank"} | Human Endogenous Retrovirus expression pipeline, as known as HERVx, is a containerized pipeline to characterize retrotranscriptome. HERVx calculates Human Endogenous Retrovirus (HERV) expression in paired-end RNA-sequencing data. |
| [l2p](https://github.com/CCBR/l2p){:target="_blank"} | List-to-pathway, or l2p, is an R package for gene set enrichment analysis that is optimized for speed. |
| [METRO](https://github.com/CCBR/METRO){:target="_blank"} | Mouse nEoanTigen pRedictOr pipeline, as known as METRO (formerly AASAP), is a pipeline to characterize the effect of a mutation on an amino acid sequences and to predict the binding of peptides to any MHC molecule using netMHCpan. |
| [MicroArrayPipeline](https://github.com/CCBR/MicroArrayPipeline){:target="_blank"} | MicroArray Analysis Pipeline, also known as MAAPster, is a comprehensive Shiny application and R package that performs transcriptome analysis of human or mouse Affymetrix gene expression data. |
| [Pipeliner](https://github.com/CCBR/Pipeliner){:target="_blank"} | An open-source and scalable solution to NGS analysis powered by the NIH's Biowulf cluster. Pipeliner provides access to a set of best-practices NGS pipelines developed, tested, and benchmarked by experts at CCBR and NCBR. |
| [Pipeliner documentation](https://github.com/CCBR/pipeliner-docs){:target="_blank"} | This repository is the main source of documentation for users and developers working with or contributing to Pipeliner. |
| [RENEE](https://github.com/CCBR/RENEE){:target="_blank"} 📦 | An open-source, reproducible, and scalable solution for analyzing RNA-seq data. The pipeline consists of a series of data processing and quality-control steps orchestrated by Snakemake, a flexible and scalable workflow management system, to submit jobs to a cluster or cloud provider. |
| [TRANQUIL](https://github.com/CCBR/TRANQUIL){:target="_blank"} 📦 | TRANQUIL or "TRna AbundaNce QUantification pIpeLine" is a Snakemake pipeline which quantifies tRNA using the mim-tRNAseq tool. |
| [wgs-seek](https://github.com/CCBR/wgs-seek){:target="_blank"} 📦 | Whole Genome-Sequencing Pipeline. Its long-term goals: to accurately call germline and somatic variants, to infer CNVs, and annotate variants. |
| [XAVIER](https://github.com/CCBR/XAVIER){:target="_blank"} 📦 | eXome Analysis and Variant explorER. Its long-term goals: to accurately call germline and somatic variants, to infer CNVs, and annotate variants. |
| [MOP2](https://github.com/biocorecrg/MOP2){:target="_blank"} | Master Of Pores V2 (MOP2) pipeline on the FRCE server. MOP2 estimates the length of mRNA poly-A tail from Nanopore reads using Tailfindr and Nanopolish. [PubMed article link](https://pubmed.ncbi.nlm.nih.gov/36723817/){:target="_blank"} |
| [DTEG](https://github.com/SGDDNB/translational_regulation){:target="_blank"} | This pipeline integrates RNA-seq and Ribo-seq to calculate translation efficiency as the number of ribosomes per gene, normalized to transcript abundance. |
| [ISOMIR](){:target="_blank"} | This pipeline performs adapter removal, small RNA profiling, and QuagmiR analysis. |
| [RiboFootPrint](https://github.com/NCI-RBL/Dockers/tree/main/workflows/RiboFootPrint){:target="_blank"} | This pipeline performs trimming of Ribo-seq reads, filters out reads mapping to non-coding RNA and remap to the transcriptome, and aggregates relative positions of read starts (split in 5' UTR, CDS, and 3' UTR). |



## 🎓 Training 

| Repository Name | Description |
| --- | --- |
| [Linear Regression](https://github.com/abcsFrederick/LinearRegression){:target="_blank"} | Repository for the linear regression materials for Statistics for Lunch. |
| [ML-Caution](https://github.com/abcsFrederick/ML-Caution){:target="_blank"} | P-hacking and abuse of machine learning: A cautionary tale. Presented at GitHub Universe - Education Day on Nov 15, 2019. |



## 📚 Other 

| Repository Name | Description |
| --- | --- |
| [Non-B GFA](https://github.com/abcsFrederick/non-B_gfa){:target="_blank"} | gfa programs for Non-B site at NCI/FNLCR. gfa is a Suite of programs developed at NCI-Frederick/Frederick National Lab to find sequences associated with non-B DNA forming motifs. |
| [spacesavers](https://github.com/CCBR/spacesavers){:target="_blank"} | This is the home of the cli, Spacesavers. Its long-term mission: to explore shared file systems, seek duplicated files, and report disk space usage. |



------------------------------------------------------------------------------------------

## 📊 Statistics BP

* [Clone Stability](https://github.com/abcsFrederick/Clone_stability){:target="_blank"}
  - This site contains the programs used in the publication "HIV Infected CD4+ T Cell Clones Are More Stable than Uninfected Clones During Long-Term Antiretroviral Therapy". Shuang Guo, Brian Luke, Amy R. Henry, Samuel Darko, Leah D. Brandt, Ling Su, David Sun, Daria Wells, Kevin W. Joseph, Dimiter Demirov, Elias K. Halvas, Daniel C. Douek, Xiaolin Wu, John W. Mellors, Stephen H. Hughes. PLoS Pathogens, 2022. [PubMed article link.](https://pubmed.ncbi.nlm.nih.gov/36044447/){:target="_blank"}



## 🔬 Imaging AI BP

* [RMS-AI](https://github.com/abcsFrederick/RMS_AI){:target="_blank"}
    - GitHub page for Predicting survival of rhabdomyosarcoma patients based on deep-learning of hematoxylin and eosin images manuscript. [PubMed article link.](https://pubmed.ncbi.nlm.nih.gov/36346688/){:target="_blank"}
* [SlideSeg3](https://github.com/abcsFrederick/SlideSeg3){:target="_blank"}
    - SlideSeg3 is an enhanced python3 version of the original SlideSeg.
* [Quick2Insight](https://github.com/abcsFrederick/Quick2Insight){:target="_blank"}
    - A framework to visualize details in volumetric datasets quickly. [Published in BioVis 2011.](https://ieeexplore.ieee.org/document/6094041){:target="_blank"}


## 🧬 Next-Generation Sequencing BP

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
* [RENEE](https://github.com/CCBR/RENEE){:target="_blank"} 📦
    - An open-source, reproducible, and scalable solution for analyzing RNA-seq data. The pipeline consists of a series of data processing and quality-control steps orchestrated by Snakemake, a flexible and scalable workflow management system, to submit jobs to a cluster or cloud provider.
* [TRANQUIL](https://github.com/CCBR/TRANQUIL){:target="_blank"} 📦
    - TRANQUIL or "TRna AbundaNce QUantification pIpeLine" is a Snakemake pipeline which quantifies tRNA using the mim-tRNAseq tool.
* [wgs-seek](https://github.com/CCBR/wgs-seek){:target="_blank"} 📦
    - Whole Genome-Sequencing Pipeline. Its long-term goals: to accurately call germline and somatic variants, to infer CNVs, and annotate variants.
* [XAVIER](https://github.com/CCBR/XAVIER){:target="_blank"} 📦
    - eXome Analysis and Variant explorER. Its long-term goals: to accurately call germline and somatic variants, to infer CNVs, and annotate variants.
* [MOP2](https://github.com/biocorecrg/MOP2){:target="_blank"}
    - Master Of Pores V2 (MOP2) pipeline on the FRCE server. MOP2 estimates the length of mRNA poly-A tail from Nanopore reads using Tailfindr and Nanopolish. [PubMed article link](https://pubmed.ncbi.nlm.nih.gov/36723817/){:target="_blank"}
* [DTEG](https://github.com/SGDDNB/translational_regulation){:target="_blank"}
    - This pipeline integrates RNA-seq and Ribo-seq to calculate translation efficiency as the number of ribosomes per gene, normalized to transcript abundance.
* [ISOMIR](){:target="_blank"}
    - This pipeline performs adapter removal, small RNA profiling, and QuagmiR analysis.
* [RiboFootPrint](https://github.com/NCI-RBL/Dockers/tree/main/workflows/RiboFootPrint){:target="_blank"}
    - This pipeline performs trimming of Ribo-seq reads, filters out reads mapping to non-coding RNA and remap to the transcriptome, and aggregates relative positions of read starts (split in 5' UTR, CDS, and 3' UTR).



## 🎓 Training BP

* [Linear Regression](https://github.com/abcsFrederick/LinearRegression){:target="_blank"}
    - Repository for the linear regression materials for Statistics for Lunch.
* [ML-Caution](https://github.com/abcsFrederick/ML-Caution){:target="_blank"}
    - P-hacking and abuse of machine learning: A cautionary tale. Presented at GitHub Universe - Education Day on Nov 15, 2019.



## 📚 Other BP

* [Non-B GFA](https://github.com/abcsFrederick/non-B_gfa){:target="_blank"}
    - gfa programs for Non-B site at NCI/FNLCR. gfa is a Suite of programs developed at NCI-Frederick/Frederick National Lab to find sequences associated with non-B DNA forming motifs.
* [spacesavers](https://github.com/CCBR/spacesavers){:target="_blank"}
    - This is the home of the cli, Spacesavers. Its long-term mission: to explore shared file systems, seek duplicated files, and report disk space usage.


