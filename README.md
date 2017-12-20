# File Explanations/Information
Bioinformatics Class Final Project by Nicole Allen, Livia Tran, and Albert Wong

### General Files:
1. mutY-sequences.gb: GenBank file containing NCBI data from 1500+ samples for mutY gene of H. pylori
2. ppa-sequences.gb: GenBank file containing NCBI data from 1500+ samples for ppa gene of H. pylori
3. mutY-accessions.seq: list of mutY Accession IDs downloaded from NCBI (corresponds to GenBank files)
4. ppa-accessions.seq: list of ppa Accession IDs downloaded from NCBI (corresponds to GenBank files)

### Nicole's Files (Order of Use):
1. ppa-accessions.seq: list of ppa gene accession numbers for later use by Albert
2. mutY-accessions.seq: list of mutY gene accession numbers for later use by Albert
3. nicole_muty_cleaning_country2.R: code to take Albert's "mutY-clean.df" and remove all rows with no country listed
4. muty-tobecleaned: CSV file output of #3
5. nicole_ppa_cleaning_country2.R: code to take Albert's "ppa-clean.df" and remove all rows with no country listed
6. ppa-tobecleaned: CSV file output of #5
7. ppa-fasta-tree: fasta file generated for Livia containing accession number and country of each ppa sequence
8. muty-fasta-tree: fasta file generated for Livia containing accession number and country of each ppa sequence
9. PhyloTreeMini_mutY.R: Phylogenetic analysis of mutY genes based on consensus sequence from each country.
10. muty_consensus_nj: contains data needed to construct mutY phylogenetic tree based on neighbor-joining calculations/analysis
11. muty_consensus_upgma: contains data to construct mutY phylogenetic tree based on UPGMA calculations/analysis
12. PhyloTreeMini_ppa.R: Phylogenetic analysis of ppa genes based on consensus sequence from each country.
13. ppa_consensus_nj: contains data needed to construct ppa phylogenetic tree based on neighbor-joining calculations/analysis
14. ppa_consensus_upgma: contains data to construct ppa phylogenetic tree based on UPGMA calculations/analysis
15. PhyloTree_Plotting_Final.R: Plots both mutY and ppa phylogenetic trees based on output from "PhyloTreeMini" files.
16. muty_tree.png: Result of mutY phylogenetic tree ggtree plot
17. ppa_tree.png: Result of ppa phylogenetic tree ggtree plot

### Livia's Files:
1. helicobacter_mutY.R:
2. helicobacter_ppa.R:
3. liv_working_muty.R: 
4. liv_working_ppa_2.R:
5. mutyplot.png:
6. ppaplot.png:
7. ppaseq.fasta: 

### Albert's Files:
