# Scripts for processing genome-wide UMI-STARR-seq data

Main script: [UMISTARRseq_pipeline.sh](UMISTARRseq_pipeline.sh)

Steps:
- Map reads with bowtie and collapse by UMIs
- Select reads with specific lengths - 150-250bp
- Create coverage BigWig files
- Call STARR-seq peaks

The raw sequencing and processed data are available from GEO under accession number [GSE183939](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE183939).  
Genome browser tracks are available at https://genome.ucsc.edu/s/bernardo.almeida/DeepSTARR_manuscript.

## Questions
If you have any questions/requests/comments please contact me at [bernardo.almeida94@gmail.com](mailto:bernardo.almeida94@gmail.com).
