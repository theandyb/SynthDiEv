## SynthDiEv

A snakemake pipeline to evaluate phasing quality using synthetic diploids constructed from male X chromosomes.

1. The pipeline assumes your raw data from chromosome X will appear in the file `data/raw/chrX.bcf`; a small example is included from the 1kGP project.
2. You will also need to provide a list of pairs of male sample names in the file `config/pairs.txt`; each line defines a single synthetic diploid individual. Again, a small example using sample names from the 1kgp are included
