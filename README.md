# AGO3-RIP-Seq-analysis

This repository contains the pipeline used to analyse AGO3-associated small RNA sequencing data described in:

De Meo E. PhD Thesis (2026)

The workflow includes:

- quality control
- adapter trimming
- genome alignment
- read counting
- normalization
- small RNA characterization

## Requirements

The pipeline was developed using:

- FastQC
- Trimmomatic
- STAR (v2.7.11a)
- Qualimap
- samtools
- bedtools
- HTSeq
- Python 3
- R (edgeR)

## Data availability

The raw sequencing data associated with this pipeline are available from the NCBI Sequence Read Archive (SRA) under BioProject accession PRJNA1482216.
