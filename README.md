# Snakemake workflow: `<name>`

[![Snakemake](https://img.shields.io/badge/snakemake-≥6.3.0-brightgreen.svg)](https://snakemake.github.io)


A Snakemake workflow for `automatically computing divergence time and summary statistics for multiple strains using neutral 4-fold degenerate sites.`

# Usage

 - Place VCF file, reference genome fasta and annotation in GFF format in the `input/` folder.
 - Adjust config file to match input files and select samples to include.
 - Run the workflow `snakemake --use-conda -c <threads>`
 - Dependencies will be installed automatically.
 - Output files are placed in the `results/` folder.
