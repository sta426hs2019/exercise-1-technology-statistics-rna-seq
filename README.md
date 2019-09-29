## RNA-Seq 

### Direct and indirect RNA seq 

RNA-seq (RNA-sequencing) uses next generation sequencing (NGS) to examine the quantity and sequences of RNA in a sample. The first step in the indirect RNA-seq involves converting the population of RNA to be sequenced into cDNA fragments. There exists direct RNA sequencing, that allows massively parallel sequencing of RNA molecules directly without prior synthesis of cDNA. [1]  

### Library preparation 

By reverse transcribing an RNA of interest, a more stable cDNA can be generated and used for further amplification. Direct ultra-high-throughput sequencing of the cDNA allows quantifiction of sequence reads and individual mapping to the source genome. [2]

### Transcriptome assembly 
The first is de novo assembly which does not require a reference genome. One example is the _Trinity_ methodology which allows sequencing of samples from fission yeast, mouse, and whitefly whose genome has yet been sequenced. [3] The second method is the genome-guided assembly which aligns the sequenced genome to a reference genome. Smith-waterman algorithm finds the alignment with the highest score and index lookup is used instead of sequence comparison.


### References

1. Ozsolak et al. Direct RNA sequencing, Nature, 2009.
2. Mortazavi et al. Mapping and quantifying mammalian transcriptomes by RNA-Seq, Nature Methods, 2008.
3. [Grabherr et al. Trinity: reconstructing a full-length transcriptome without a genome from RNA-Seq data, 2011](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3571712/)
