# MarginAlign BAMs
`marginAlign` is a probabilistic aligner that uses an input _guide_ alignment as a starting point then realignes the
bases with a hidden Markov model (HMM). The HMM is trained using expectation maximization. The resulting alignments are
typically more accurate.

### Chained BAMs
By default `marginAlign` chains the guide alignment so that each read has one maximal (by length) alignment to the
reference.

| Chrom | BAM                                                                                      |
|  ---  | ---------------------------------------------------------------------------------------- |
| Chr10  | [BAM](https://s3-us-west-2.amazonaws.com/miten-human-genome-paper/chr10/chr10_realigned.bam)   |
| Chr20 | [BAM](https://s3-us-west-2.amazonaws.com/miten-human-genome-paper/chr20/chr20_realigned.bam) |
| ChrX | [BAM](https://s3-us-west-2.amazonaws.com/miten-human-genome-paper/chrX/chrX_realigned.bam) |



