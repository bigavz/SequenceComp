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

=====================

installation:  

applet, reference genes, zip into file using proprietary version of http://en.wikipedia.org/wiki/Compression_of_Genomic_Re-Sequencing_Data

this file would include user-side reference sequences and applet for extration

extraction:

find reference characters & substitute

=====================

current flow:

researchers collect samples, isolate DNA -> next-gen sequencing labs [create sequence] => researchers

this final step requires NGS labs to deliver sequence data via mail using tons of HDDs

e-mail compression is possible for human genomes (see above)

but in ecology, the problems would be more complex.  further investigation is needed on the role of this tool in this ecosystem