# Minimal Working Example
An HTML file of differential expression analysis using R.

### Project Title
Identification of critical candidate genes during Melanoma development and progression based on RNA sequencing data.

### Aim of the Project
This study aims to identify the candidate genes during the development of melanoma by performing a step-by-step RNA-Seq analysis approach comparing gene expression of 
cell lines derived from different melanoma development stages (radial growth phase [RGP], vertical growth phase [VGP ], metastasis [MET]) with the expression of Normal 
Human Epidermal Melanocytes (NHEMs) and each other. 
The identification of the differential expressed genes in each developmental step will lead to in-depth molecular understanding of melanoma developmental steps and 
help to identify new prognostic markers for early melanoma detection and therapeutic targets to develop efficient melanoma treatment options.

### Materials and Methods 
RNA Sequencing data was processed and analyzed by using a bioinformatics pipeline.
-	Raw reads (FASTQ files) will be first quality-checked using FastQC v0.11.9 to ensure high read quality. 
-	Filtered reads will be then aligned to the human reference genome (GRCh38/gencode v29.0) using the STAR Aligner tool v2.7.10a.
-	Mapped reads will be counted to generate the Counts table by using of featureCounts tool v2.0.0. 
-	Differential gene expression analysis was e analyzed using DESeq2 v1.34.0 package within R programming language v4.1.3 and RStudio v2022.2.0.443.

### Dataset information
The RNA-Seq dataset used in this study is a standard Illumina data set (Paired-end) obtained from Prof. Dr. Melanie Kappelmann-Fenzl. The RNA-Seq dataset was shared 
through the sFTP server from the supercomputer cluster server of the Deggendorf Institute of Technology. In addition, the data is publically available in the NCBI
database (https://www.ncbi.nlm.nih.gov/bioproject/PRJNA839865).




