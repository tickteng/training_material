This directory contains the data for training material

Step-by-step information can be found here: https://wool-hour-a95.notion.site/EFSA-training-eab42c4d48e64a7cb8a720941e8b9942?pvs=4

List of folders and content:

./aln/sample04.bam.gz: alignment file of sample04 to Hg38.

./db/:fluadb.fa contains reference sequence obtained from https://gisaid.org/.

./fastq/: subset of fastq files obtained from public database
1. sample01: Nanopore reads, Influenza A, subset from SRR23318372
2. sample02: Nanopore reads, Influenza A, subset from https://doi.org/10.5066/P93VXVGO
3. sample03: Nanopore reads, Influenza A, inhouse (subset)
4. sample04: Illumina reads, metagenomics, subset from SRR10971381
5. sample05: Illumina reads, Influenza A, SRR18273474 

./pdf/: presentations and step-by-step guide.

./script/: plotcov.rscript is an rscript to plot the coverage across the genome using the output from samtools depth.