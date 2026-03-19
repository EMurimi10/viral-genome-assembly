# Viral Genome Assembly Pipeline

A Snakemake pipeline for de novo assembly and classification 
of unknown viral paired-end short reads from human samples.

## Pipeline Steps
1. FastQC — Raw read quality control
2. Trimmomatic — Adapter & quality trimming
3. Bowtie2 — Human host read removal
4. SPAdes — De novo viral genome assembly
5. Kraken2 — Viral taxonomic classification
6. QUAST — Assembly quality evaluation

## Requirements
- conda/mamba
- Snakemake
- bowtie2
- kraken2

## Author
Eric Muthanje
