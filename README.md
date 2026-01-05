# Code to Perform a Genome Build Liftover

Sometimes it is necessary to perform a liftover from a newer GRC Chromosome Build (GRCh38) to an older one (GRCh37) or vice versa. This ensures your coordinates align when comparing different datasets and/or reference panels and that the variants can therefore be correctly combined.

This script takes summary data from https://pubmed.ncbi.nlm.nih.gov/34012112/ and uses the UCSC Liftover tool to convert it from GRCh38 format back to GRCh37 (also known as hg19).
