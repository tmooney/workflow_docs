# WUSTL oncology genomic workflows

Workflows definitions and configuration focused on reusable, reproducible analysis pipelines for genomics data.

The Division of Oncology, in collaboration with the . . .

## Available pipelines
- Fully tested on all platforms:
immunogenomics, somatic human and non/human, germline human, RNA-seq (human/non-human), pvactools
- Used extensively but not fully tested/vetted for cloud:
bisulfite sequencing, etc

## Options for running the workflows
These workflows are portable and we provide instructions for configuring them to run on multiple platforms:
- Google Cloud Compute
- Terra
- WUSTL RIS compute cluster
- Locally (laptop/desktop)

## Where to get required inputs
In addition to your genomic data (often fastqs or unaligned bams), these pipelines require inputs like reference genomes, gene annotations.  For convenience, we provide *reference bundles* that contain the inputs for many human and mouse pipelines, as well as *example yaml files* that are prepopulated with most of the needed data.

We also provde a more complete guide on *creating your own reference bundle*.



