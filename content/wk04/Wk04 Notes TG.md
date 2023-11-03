# Learning Objectives Week 4

1. Understand the Burroughs-Wheeler Alignment (BWA) algorithm and its applications.
   
    a. Derived from the BW transform, it is used to sift through the massive amounts of data from NGS. The BW transform is a data compression algorithm that plays a crucial role in the BWA underlying algorithms
   
     b. BWA uses two different algorithms for aligning NGS reads to a reference genome: the BWA-backtrack algorithm for short reads and the BWA SW algorithm for longer reads
3. Differentiate between BWA and other alignment algorithms (like BLAST).
     a. 
5. Understand why we should **not** put large result-files into git repos.
6. Understand the purpose of generating alignment indexes.
7. Use samtools to view and count the number of aligned reads.
8. Use samtools flagstat to summarize an alignment result.
9. Understand the important fields of a SAM format.
