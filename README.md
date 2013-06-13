SequenceComp
=========================================
Sequence compression for ecological macrogenomic sequencing
Based on the ideas presented by Christley, Lu, et al. (http://bioinformatics.oxfordjournals.org/content/25/2/274.full)
for human genomes compared to reference human genome with SNP marker location (known markers for regions of difference)

This program would be for *any* macrogenomic data set, including partial genomes
Works by exploiting user-side data - reference genes

Import sequence data (on order of TB)
Load sequence serially into buffer
Diff buffer with reference sequence (parallel sequence alignment)
-reference sequences will be list of most highly preserved genes
-diff only large sequences
-reference call must be geneID(a,b) a,b are base pair indeces

installation:  
applet, reference genes

extraction:
find reference characters & substitute


