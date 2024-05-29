# csat_sourmash_scaffold

## Scaffolding assemblies using split HiC scaffolded chromosomes
### - All reference chromosomes have IDs in this format: {Sample_ID}.chr{number}
### - All reference chromosomes are the autosomal chromosomes from 1 to 9 and either the X or Y sex chromosome

## Installation:
### sourmash and RagTag must be installed:

`conda create -n scaffold -c bioconda sourmash ragtag jupyter`

`conda activate scaffold`

`pip install pandas`

`pip install biopython`