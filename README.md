#Practicl assignment for transcriptomics-course-at-the-University-of-Vic
The aim of this practical is to analyse a transcriptomics GEO series obtained from 
Affymetrix microarrays or RNA-seq. You will need to follow the steps:
• Choose a GEO data set based on a platform that we have seen in class:
a. Affymetrix 3’IVT (slide 11 lists the most frequent families of those arrays)
b. Illumina RNA-seq data having row counts available (usually as a 
supplementary file)
This series should ideally contain between 6 and 24 samples, at least 2 
conditions and at least 3 samples by condition
1. Describe the objective of the GEO project, the array and the design of the 
experiment
2. Download raw data from GEO (supplementary file)
3. Perform quality assessment. Comment results and decide whether they have 
enough quality to be analysed and remove outlier samples if necessary
4. Normalize data
5. Perform sample distribution (aggregation). Comment on this distribution
6. Obtain differentially expressed genes (DEG). Choose a method and justify the 
variables included in the model, each step performed to obtain the list and DEG
selection criteria. Specify the thresholds taken to obtain the final list of DEG
7. Annotate the results to HGNC symbols
8. Generate a volcano plot and a heat map for the results
9. Drive some conclusions using the description on the data given in GEO
