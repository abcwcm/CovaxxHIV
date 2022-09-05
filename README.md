

[![DOI](https://zenodo.org/badge/470073692.svg)](https://zenodo.org/badge/latestdoi/470073692)


# HIV and Covid vaccine

This repo contains the code related to the bulk RNA-seq data presented in:

>Stevenson EM, Terry S, Copertino D, Leyre L, Danesh A, Weiler J, Ward AR, Khadka P, McNeil E, Bernard K, Miller IG, Ellsworth GB, Johnston CD, Finkelsztein EJ, Zumbo P, Betel D, Dündar F, Duncan MC, Lapointe HR, Speckmaier S, Moran-Garcia N, Papa MP, Nicholes S, Stover CJ, Lynch RM, Caskey M, Gaebler C, Chun TW, Bosque A, Wilkin TJ, Lee GQ, Brumme ZL, Jones RB. SARS CoV-2 mRNA vaccination exposes latent HIV to Nef-specific CD8+ T-cells. Nat Commun. 2022 Aug 19;13(1):4888. doi: 10.1038/s41467-022-32376-z. PMID: 35985993; PMCID: PMC9389512.

----------------------------------

The [`makefile`](https://github.com/abcwcm/CovaxxHIV/blob/main/preprocessing/makefile) in the `preprocessing` directory contains all details of the alignment, QC, and read count procedure. 

The [`code_for_figure` directory](https://github.com/abcwcm/CovaxxHIV/tree/main/code_for_figures) **contains the read counts and metadata** that are needed to run the code in the `.Rmd` document to generate the figures of the publication that were based on the bulk RNA-seq data set. The HTML file is the fully compiled result of the Rmd file.

*The raw reads have not been submitted to a repository due to this being patient data.* If needed, we may be able to provide [privay-protecting pBAM files](https://www.sciencedirect.com/science/article/pii/S0092867420312332) via [ptools](https://github.com/ENCODE-DCC/ptools).

Don't hesitate to get in touch with abc(at)med.cornell.edu.


![](WCM_MB_LOGO_HZSS1L_CLR_RGB.png)


