# Whole-exome and RNA sequencing data sets for MC38A and MC38B

The raw sequencing data sets have arrived and backed up on:

```
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/:

gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290303045/:

gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290303045/00_fastq/:
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290303045/00_fastq/A-WES_R1_001.fastq.gz
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290303045/00_fastq/A-WES_R2_001.fastq.gz
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290303045/00_fastq/B-WES_R1_001.fastq.gz
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290303045/00_fastq/B-WES_R2_001.fastq.gz
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290303045/00_fastq/T-WES_R1_001.fastq.gz
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290303045/00_fastq/T-WES_R2_001.fastq.gz
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290303045/00_fastq/md5sum_list.txt

gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290309823/:

gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290309823/00_fastq/:
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290309823/00_fastq/A-RNA_R1_001.fastq.gz
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290309823/00_fastq/A-RNA_R2_001.fastq.gz
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290309823/00_fastq/B-RNA_R1_001.fastq.gz
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290309823/00_fastq/B-RNA_R2_001.fastq.gz
gs://musc-tcr-transfer/data/20191129-mc38-sequencing/30-290309823/00_fastq/md5sum_list.txt
```

Will close this issue once I put the proper pointers up in the README file.

- `A`: MC38 (that we have been using for our other experiments so far -- see the `MC38A` folder)
- `B`: MC38B (from Aaron Ring; we used this for the actual tumor experiments so TCRs should be specific to this -- see the `MC38B` folder)
- `T`: bulk T cells from B6 mice (this is the mouse we injected MC38B subcatenously)