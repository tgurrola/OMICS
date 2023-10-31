# Week 3 Assignment instructions
1. Use seqkit stats to generate basic statistics about about the multiplexed data.
2. Using the `data/sample_sheet.csv` file as a sample sheet, demultiplex the reads in `wk03/data/multiplexed.fq` into individual files. The sample sheet defines the barcodes on the 3' and 5' ends as they appear on the sequence. Save the files to solution/{sample_name}.fastq.
3. You should end with the following directory structure:
```bash
solution/SRR23803536.fastq
solution/SRR23803537.fastq
solution/SRR23803538.fastq
solution/SRR23803539.fastq
```
## Trim the barcodes
4. Now that we know which sample each read belongs to, the barcode is now extranious information. We should remove it from the read
5. utilize seqkit to create gzipped fastq files that only contained the trimmed sequence. You should end with the following directory structure:
```bash
solution/SRR23803536.trimmed.fastq.gz
solution/SRR23803537.trimmed.fastq.gz
solution/SRR23803538.trimmed.fastq.gz
solution/SRR23803539.trimmed.fastq.gz
```
6. Use seqkit stats to generate basic statistics about about the demultiplexed and trimmed data.
# Refection Questions
 - Are there an equal number of reads from each sample?
 - Are the read lengths the same between each sample?
   
