# abraomAnalysis

Denis Moura¹<br>
1 - Laboratório de Imunopatologia Keizo Asami - Universidade Federal de Pernambuco

This project aims to extract information for clinical variants in the ABraOM database.

In this project we analyzed which variant annotations of the five Primary Familial Brain Calcification genes are present in the  SABE609 South-American cohort. The genes are SLC20A2, XPR1, PDGFB, PDGFRB, KIAA1161 and JAM2.

For this, we have used pandas to access the ABRaOM_60+_SABE_609_exomes_annotated.csv file downloaded from ABraOM (http://abraom.ib.usp.br/), and compared the variants to ClinVar (https://www.ncbi.nlm.nih.gov/clinvar/) database.

We were able to find 10 different PFBC-causing variants in the SABE609 cohort, and their respective frequency in that population.
Three variants were found in the SLC20A2 gene, with a total frequency of 5.91% of the alleles (p.A480T, p.G304S and p.R254Q).
The remaining variants were found in the PDGFRB gene, with a total frequency of 12.31% of the alleles (p.G1040V, p.R502Q, p.E485K, p.T464M, p.Q406R, p.P345S and p.I29F).
Summing all allele frequencies for PFBC-causing variants, we extracted a probability of 18.31% of an individual from SABE609 population to have at least one PFBC-causing variant.
