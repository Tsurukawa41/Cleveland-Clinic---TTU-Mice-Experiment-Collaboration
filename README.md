# Cleveland Clinic & TTU Mice Experiment Collaboration

## Project Overview

The project uses multiomics data from CCF in an experiment with mice subjected to wheel exercise and/or treated with an injection of ammonium acetate (AmAc).

## Methodology

### Bivariate Ranking
We developed a **bivariate ranking methodology** to prioritize genes based on their significance across both transcriptomic and proteomic datasets. This technique involves the following steps:

1. **Data Normalization**: 
    Both transcriptomic and proteomic data are preprocessed to ensure comparability. Z-scores are applied to normalize expression levels or LFQ intensities.

2. **Preliminar Feature Selection**: 
    We apply Relief-F (k=3) to select 100 genes from each dataset before performing the bivariate ranking analysis.
   
3. **Bivariate Ranking**:
    We then rank genes based on a combined cross-validation score that integrates both transcriptomic and proteomic performances.

### Figures
We provide figures to illustrate the bivariate gene performances (located in the `figures/` folder):

### Results Overview
The results are stored in the Excel worksheet `Results_TTU.xlsx`, which contains the top 100 genes identified in each of the the transcriptomic and proteomic datasets.

---

## Contact

For any questions, please contact: [contact_email@ttu.edu](mailto:contact_email@ttu.edu)