
# calcareous-sponges_comparative-genomics
This project aims to address the following key questions regarding a new species of calcareous sponges:
1) its phylogenetic position
2) does it have mt-mRNA editing?
3) how many mt-chromosomes?
4) the mechanism of editing loss (if there are any clues).





To achieve these targets, we first constructed the phylogenetic tree twice: once based on 18S ribosomal RNA and a second time based on 28S ribosomal RNA. The two phylogenetic trees can be found in the following file: 28s_besttree and my_tree.raxml.bestTree

Secondly, we extracted the DNA of the eleven known mitochondrial genes based on the main findings of the following paper : https://pubmed.ncbi.nlm.nih.gov/26725199/ .                                                We then used these genes to search against our DNA and mRNA assemblies of the new species, extracting the best sequences based on coverage and similarity. These sequences can be found here:
DNA_seqs: Contains the eleven DNA sequences, with each file named according to the gene.
mRNA_seqs: Contains the eleven mRNA sequences, with each file named according to the gene.   

Thirdly, we compared the DNA and mRNA sequences for the 11 genes, and saved the alignment results in the following file: aligned_sequences.fasta. Interestingly, we found that this strain is not completely missing RNA editing, as some genes exhibit editing while others do not. For the genes that do show editing, it appears that the editing is not uniform. Unlike other sponges where, for example, a "C" followed by a "T" often results in the insertion of two additional "T"s (changing "CT" to "CTTT"), 
The observed pattern tends to be clustered in specific regions of the gene, typically toward the middle, rather than spread evenly across the entire gene. This suggests that there may be regulatory elements influencing the editing process in this species. Furthermore, this species might represent an intermediate stage between those that have completely lost RNA editing and those that retain it fully. This discovery raises several intriguing research questions that warrant further investigation.
