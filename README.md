# **RNA-Seq Analysis: Quality Control and Read Mapping**

## **Project Overview**
This project covers RNA-Seq data preprocessing, focusing on quality control, trimming of paired-end sequencing reads, and initial read mapping. I worked with colon cancer and normal tissue samples using tools like FastQC.

## **Objectives**
The main goals were to clean and preprocess RNA-Seq data, improve read quality through trimming, and initiate read mapping to a reference genome.

## **Data**
The dataset includes paired-end reads from:
- **SRR6191645**: Colon cancer sample.
- **SRR6191646**: Normal tissue sample.

Data was retrieved from the NCBI SRA database.

## **Quality Control and Trimming**
**Tools Used**: FastQC, Trimmomatic
1. **Quality Check**: Assessed read quality using FastQC, noting sequence and GC content.
2. **Trimming**: Removed adapters and low-quality bases, ensuring a minimum read length of 80 bp.
3. **Post-trimming Check**: Improved quality was confirmed by running FastQC again.

**Results**:
- Read count reduced (~38M reads/sample after trimming).
- Read length between 80-150 bp.
- Improved overall read quality scores.

## **Read Mapping **
**Tool Used**: HISAT2
- Prepared the reference genome and initiated alignment using HISAT2.
- Conversion and sorting of SAM/BAM files were noted.


## **Tools**
- **SRA Toolkit**: Downloading sequencing data.
- **FastQC**: Read quality assessment.
- **Trimmomatic**: Adapter and quality trimming.
- **HISAT2**: Reference genome indexing and read alignment.

