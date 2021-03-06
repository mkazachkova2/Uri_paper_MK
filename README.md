# *Aneuploidy-induced cancer vulnerability to mitotic checkpoint inhibition*

### This repo contains some of the analysis done for the paper *Aneuploidy-induced cancer vulnerability to mitotic checkpoint inhibition* by Cohen-Sharir et al. 

- link to paper in Nature: https://www.nature.com/articles/s41586-020-03114-6
- link to bioRxiv: https://www.biorxiv.org/content/10.1101/2020.06.18.159038v1.full   

*FIGURE X* and *Supplementary Extended Data Figure X* notebooks match up with the published version of the manuscript  

## Brief description of the figures and code availability:

**Figure 1**: Differential sensitivity of aneuploid cancer cells to inhibition of the spindle assembly checkpoint.
- code available for 1b, 1d-h  (Figure 1.ipynb)

**Figure 2**: The effect of aneuploidy on cellular sensitivity to SACi in isogenic human cell lines.  
**Figure 3**: Transcriptional, cellular and karyotypic characterization of SACi in aneuploid cells.  
**Figure 4**: Altered spindle geometry and dynamics, and increased dependency on the mitotic kinesin KIF18A, in aneuploid cancer cells.
- code available for 4e (Figure 4.ipynb)

**Extended Data Figure 1**: Increased sensitivity of aneuploid cancer cells to genetic inhibition of the spindle assembly checkpoint.
- code available for 1b-c, 1g-k (Extended Data Figure 1.ipynb)

**Extended Data Figure 2**: Genomic and phenotypic features associated with the degree of aneuploidy in human cancer cell lines.
- code available for 2a-e (Extended Data Figure 2.ipynb)

**Extended Data Figure 3**: Increased sensitivity of aneuploid cancer cells to SACi remains significant when associated genomic and phenotypic features are controlled for.
- code available for 3a-i (Extended Data Figure 3.ipynb)

**Extended Data Figure 4**: Reduced sensitivity of aneuploid cancer cells to chemical inhibition of the spindle assembly checkpoint
- code available for 4a-e (Extended Data Figure 4.ipynb)

**Extended Data Figure 5**: Isogenic model systems of near-diploid and aneuploid cell lines.  
**Extended Data Figure 6**: The effect of aneuploidy on cellular sensitivity to SACi in isogenic human cell lines.  
**Extended Data Figure 7**: Time-dependent increased sensitivity of aneuploid cancer cells to genetic and chemical SACi.  
**Extended Data Figure 8**: Transcriptional and cellular characterization of SACi in aneuploid cells.  
**Extended Data Figure 9**: Increased sensitivity of aneuploid cancer cells to perturbation of the mitotic kinesin KIF18A.
- code available for 9f-k (Extended Data Figure 9.ipynb)

**Extended Data Figure 10**: Increased sensitivity of aneuploid cells to KIF18A inhibition.
- code available for 10a-i (Extended Data Figure 10.ipynb)

## Brief description of the tables and code availability:

**Supplementary Table 1**: Chromosome-arm copy number calls and aneuploidy scores for 997 human cancer cell lines.  
- "make_CCLE_arm_calls.R" takes the CCLE2 published ABSOLUTE data as input and calls the number of arm-level CNAs for each cell line (*anueploidy score*).
- "make_aneuploidy_calls.R" takes that output and calls the 'many_arm_events' column based on the upper and lower quantiles.  


**Supplementary Table 2**: Genetic dependencies of highly-aneuploid cancer cells.
 - code for Limma runs found in Limma folder. Files: limma_drive.R and limma_achilles.R for Drive and Achilles, respectively

**Supplementary Table 3**: Functional annotation enrichment analysis of aneuploidy- associated genetic dependencies.   
**Supplementary Table 4**: mRNA expression differences between near-euploid and highly- aneuploid cancer cells.
- code for Limma run found in expression/limma_differential_expression.R

**Supplementary Table 5**: Chemical sensitivities of highly-aneuploid cancer cells.
- code for Limma runs found in limma/drug_comparisons. Files: using_limma_CTD.R, using_limma_GDSC.R, using_limma_prism.R

**Supplementary Table 6**: Cancer cell line sensitivity to the SAC inhibitor reversine.  
**Supplementary Table 7**: Gene expression profiles of HCT116 and HPT cells exposed to SAC inhibitors.  
**Supplementary Table 8**: Association between aneuploidy levels and KIF18A mRNA and protein expression levels.


Code written by: Mariya Kazachkova and James McFarland (contact: *jmmcfarl -at- broadinstitute.org*)


