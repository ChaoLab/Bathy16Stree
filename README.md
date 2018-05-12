# Bathy16Stree
Methods to make 16S rRNA gene tree of Bathyarchaeota and intermediate files

Files 
1. Original fasta: CKY_BS90_kgf.de.fasta
2. Trimmed alignment: CKY_BS90_kgf.de.sina.trim5.fasta
3. Tree file: S-6WHuekat59NLLehFrMWA_newick.txt.mdf
4. Assignment of subgroup: sseqs_subgroup.txt

Methods to make 16S rRNA gene tree of Bathyarchaeota

16S rRNA gene sequences were collected from SILVA SSU database version 128
(sequences of Bathyarchaeota and Group C3; > 750bp) and Xiang’s Peatland MCG
sequences (Xiang et al. 2017), all sequences were clustered at
90% identity using Usearch v10.0.240 (https://www.drive5.com/usearch/), then
16S rRNA gene sequences from available Bathyarchaeota genomes in public
database, anchor sequences from Kubo et
al. and outgroup sequences of Crenarchaeota, YNPFFA group and Korarchaeota
were added (Kubo et al. 2012). All sequences were aligned using
SINA v1.2.11 (vision 21227) with SSU arb database version 128, and poor aligned
columns (gaps in 50% or more of the sequences) were deleted by using trimAl
v1.4.rev15 (Capella-Gutiérrez et
al. 2009; Ludwig et al. 2004;
Pruesse et al. 2012). Phylogenetic
analyses of 16S rRNA sequences were inferred by Maximum Likelihood implemented
in RAxML 8.0 on The CIPRES Science Gateway using the GTR+GAMMA model and RAxML
halted bootstrapping automatically (Miller et al. 2010;
Stamatakis 2014).

 

 

 

Reference:

 

Capella-Gutiérrez
S, Silla-Martínez JM, Gabaldón T. trimAl: a tool for automated alignment
trimming in large-scale phylogenetic analyses. Bioinformatics 2009;25:
1972-3.

Kubo K, Lloyd KG, Biddle JF
et al. Archaea of the Miscellaneous Crenarchaeotal Group are abundant,
diverse and widespread in marine sediments. ISME
J 2012;6: 1949-65.

Ludwig W, Strunk O, Westram R et al. ARB: a software environment for sequence data. Nucleic Acids Res 2004;32: 1363-71.

Miller MA, Pfeiffer W, Schwartz T. Creating the CIPRES Science
Gateway for inference of large phylogenetic treesGateway Computing Environments Workshop (GCE), 2010: IEEE, 2010,
1-8.

Pruesse E, Peplies J, Gloeckner FO. SINA: Accurate
high-throughput multiple sequence alignment of ribosomal RNA genes. Bioinformatics 2012;28: 1823-9.

Stamatakis A. RAxML version 8: a tool for phylogenetic analysis
and post-analysis of large phylogenies. Bioinformatics
2014;30: 1312-3.

Xiang X, Wang R, Wang H
et al. Distribution of Bathyarchaeota Communities Across Different
Terrestrial Settings and Their Potential Ecological Functions. Sci Rep 2017;7: 45028.


