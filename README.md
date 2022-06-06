# Project2DFINAL
In this project, I will be using data from the NCBI database for Multiple Sequence Alignment and Phylogenetic Trees. The NCBI database is a public biomedical databases with software tools for analyzing molecular and genomic data, and research. The database can be found here: https://www.ncbi.nlm.nih.gov/.   

I used the protein search on the database to download and create a compressed fasta file of the amino acid sequence for the target protein RdRp. I found the target protein RdRp in SARS-CoV-2 and chose 5 other RdRp protein sequences in other viruses similar to COVID-19 including bat coronavirus and others. These other viruses include Porphyridium Purpureum Toti-Virus, Japanese Plum-Yew deltapartitivirus, Lycopod mitovirus, and Chinese swamp cypress mitovirus. 

The multiple sequence alignment was used to identify evolutionary patterns between SARS-CoV-2 and the other viruses listed above. This was analyzed in a phylogenetic tree that can identify common ancestors and similarities between the viruses.   

Furthermore, I will also be using the RCSB PDB database, which is the protein  data bank database. the protein data bank database is a repository for all the information on 3D structures of proteins, nucleic acids, and complex assemblies that helps students and researchers understand aspects in biomedicine. The database can be found here: https://www.rcsb.org  

I used this database to perform Structural Bioinformatics and 3D Protein Measurements. Because of R's exceptional functionalities, I did not directly download any files, they were read in with the package 'bio3d' using the read.pdb() function.   Structural Bioinformatics was used to identify the structure of RdRp target protein through the use of 6NUR from the pdb database. The 3D protein measurements of 6NUR was taken as well as protein measurements from an array of other target proteins of RdRp in other viruses. These viruses are different from the viruses used for Multiple sequence Alignment and Phylogenetic Tree. These protein structures are listed here:

1. 6NUR - SARS-Coronavirus NSP12 bound to NSP7 and NSP8 co-factors 
2. 7B3D - Structure of elongating SARS-CoV-2 RNA-dependent RNA polymerase with AMP at position -4  
3. 5I62 - Crystal structure of the insertion loop deletion mutant of RdRp of a human picorbirnavirus 
4. 6L4R - Crystal structure of Enterovirus D68 RdRp 
5. 3UQS - Crystal structures of murine norovirus RdRp 
6. 5K5M - Co-Crystal Structure of Dengue Virus Serotype 2 RdRP with Compound 27 

The goal of this project is to see how strcturally similar the target protein of COVID-19, RdRp, is in hopes of potentially finding a methodical antiviral drug that can combat and inhibit the viral replication of COVID-19 and similar viruses. 

Scientific Question: Is the target protein, RNA-dependent RNA polymerase (RdRp) in SARS-CoV-2, structurally similar to the RdRp target proteins in other related viruses? 

Scientific Hypothesis: If the RdRp target protein of SARS-CoV-2 is analyzed through multiple sequence alignment and structural bioinformatics, then the RdRp protein sequence of SARS-CoV-2 will be structurally similar to at least 30% of the compared RdRp target proteins of other related viruses.

The following project is built around the following research articles below: 

Aftab, S.O., Ghouri, M.Z., Masood, M.U. et al. Analysis of SARS-CoV-2 RNA-dependent RNA polymerase as a potential therapeutic drug target using a computational approach. J Transl Med 18, 275 (2020). https://doi.org/10.1186/s12967-020-02439-0

Ghosh, D., Ghosh Dastidar, D., Roy, K. et al. Computational prediction of the molecular mechanism of statin group of drugs against SARS-CoV-2 pathogenesis. Sci Rep 12, 6241 (2022). https://doi.org/10.1038/s41598-022-09845-y

Jiang, Yi et al. “RNA-dependent RNA polymerase: Structure, mechanism, and drug discovery for COVID-19.” Biochemical and biophysical research communications vol. 538 (2021): 47-53. doi:10.1016/j.bbrc.2020.08.116

Lastly, the following files are needed to recapitulate the code:
1. R Notebook
2. fasta file: RdRp.fasta
3. Following pdb files: 6NUR.pdb, 7B3D.pdb, 6L46.pdb, 5K5M.pdb, 5I62.pdb, and 3UQS.pdb

All of the files have been uploaded and can be found above.


