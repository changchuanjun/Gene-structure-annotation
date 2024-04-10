# Gene structure annotation
Protein-coding genes were predicted from the genome using the BRAKER3 pipeline[1] that integrates RNA-Seq and protein homology information. RNA-Seq reads were aligned to the soft masked genome using HISAT2 (v2.2.1). Protein sequences from related species were downloaded from NCBI (https://www.ncbi.nlm.nih.gov/) and aligned to the genome as the protein homology evidence.

[1]BRAKER3: Fully automated genome annotation using RNA-Seq and protein evidence with GeneMark-ETP, AUGUSTUS and TSEBRA
Lars Gabriel, Tomáš Brůna, Katharina J. Hoff, Matthis Ebel, Alexandre Lomsadze, Mark Borodovsky, Mario Stanke
bioRxiv 2023.06.10.544449; doi: https://doi.org/10.1101/2023.06.10.544449
