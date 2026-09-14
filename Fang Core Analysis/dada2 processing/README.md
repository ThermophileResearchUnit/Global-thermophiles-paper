## DADA2 Workflow

This directory contains scripts used to process raw Illumina amplicon sequencing data using a modified DADA2 pipeline. For this workflow you will need to download the raw sequencing files from NCBI Sequence Read Archive

Workflow steps:
1. Demultiplex raw sequencing reads
2. Remove sample barcodes, primers, and adapter sequences
3. Perform read quality filtering and trimming
4. Learn sequencing error rates
5. Dereplicate reads
6. Infer ASVs using the DADA2 algorithm
7. Merge paired-end reads
8. Remove chimeric sequences
9. Assign taxonomy using the SILVA database
10. Generate ASV and taxonomy tables for downstream analysis

An knit HTML output of the processing used to generate the data used in this analysis is included (FangCore_dada2_515f-806r_miseq2x250.html). The output files are in the folder: dada2_output
