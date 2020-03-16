# PangenomePipelineScripts
A repository for the scripts I developed to do pangenome inference using SPAdes, prokka, and Roary.

Start within a directory with read data present and run assembly_parallel.py

quast_run.py can be used to generate stats on the assemblies. I used the M. bovis reference genome to help with assembly validation

prokka_run.py should be used in a directory with only assemblies. will generate the GFF files needed for Roary
