# edit_fasta_for_newick_v2
Input:

A multiple sequence alignment file (example.aln)

Output:

an edited multiple sequence alignment file (otu_alignment_w_edited_header.aln)


Description:

In order to construct a newick string, fasta headers must be edited to remove extraneous header info. Headers are parsed and edited to contain only the ID/name which will be used in the newick string for constructing a phylogenetic tree.

Updates to v2:

fully automated.
deals with "NR_" IDs instead of "gi_" numbers.
element positions are changed due to change in fasta header information and therefore how each header is parsed is also different.
