# TCGA_PanCancer_Genotyping

Last updated: 03/20/2022

## Description
We present a workflow for pre-processing and imputation of the  9000 patients enrolled in the TCGA. The protocol is developed around the structure of TCGA, but it can be adapted to explore other genotyping array data sets.

The code and data deposited here were used to generate the results and resource files for the Sayaman, Saad et al., Immunity 2021 and Carrot-Zhang et al., Cancer Cell 2020 papers.

Code contained herein are meant as a guide and should be modified and adapted to match your server specifications and directories.


## Citations
Please cite Sayaman, Saad et al., Immunity 2021 when using the data and code contained here in, and downloading the TCGA QC and HRC imputed genotyping data. 
* Sayaman, Saad et al., Immunity (2021). Germline genetic contribution to the immune landscape of cancer. https://doi.org/10.1016/j.immuni.2021.01.011
* Chambwe, Sayaman, et al., Analysis of Germline-Driven Ancestry-Associated Gene Expression in Cancers.

Please additionally cite: Carrot-Zhang et al., Cancer Cell 2020 when referencing ancestry assignments and downloading the TCGA QC and HRC imputed genotyping data.
* Carrot-Zhang et al., Cancer Cell (2020). Comprehensive Analysis of Genetic Ancestry and Its Molecular Correlates in Cancer. https://doi.org/10.1016/j.ccell.2020.04.012


## Code Contributors
* Rosalyn W. Sayaman, Ph.D., University of California, San Francisco: rwsayaman@gmail.com
* Donglei Hu, Ph.D., University of California, San Francisco
* Scott Huntsman, University of California, San Francisco

## Acknowledgment
* Nyasha Chambwe, Ph.D., Feinstein Institutes for Medical Research

## Senior Authors
* Elad Ziv, Ph.D., University of California, San Francisco
* Andrew D. Cherniack, Ph.D., The Broad Institute of Harvard and MIT/Dana-Farber Cancer Institute/Harvard Medical School
* Rameen Beroukhim, Ph.D., The Broad Institute of Harvard and MIT/Dana-Farber Cancer Institute/Harvard Medical School/Brigham and Women’s Hospital


## Contents

### Before you begin

The protocol describes specific steps using TCGA datasets However, this can be applied in other datasets with similar structure.

* **System Requirements**

* **Apply for dbGaP Authorization**

* **Software Installation**
  * PLINK
  * R/Bioconductor

### Analysis

* **Code**
  * Quality Control Analysis of Germline Data
  * Stranding
  * Genotype Imputation

  
## Resources
1. TCGA QC and HRC Imputed Genotyping Data  
   * Access to the TCGA original birdseed (GDC Data Portal: https://portal.gdc.cancer.gov/) and pre-processed quality controlled genotyping data imputed to HRC generated in Sayaman et al., Immunity 2021 requires GDC controlled access permission approval.
   * The quality controlled and HRC imputed genotyping data and the UCSF ancestry assignments were contributed towards ancestry analyses (Carrot-Zhang et al., 2020) and are accessible at the GDC publication page (https://gdc.cancer.gov/about-data/publications/CCG-AIM-2020).
   
   * See folder: "TCGA QC HRC Imputed Genotyping Data used by the AIM AWG (from Sayaman et al)"
     * Controlled Access data include:
       * QC Unimputed Genotyping Data
       * HRC Stranded Unimputed Genotyping Data
       * 1000 Genomes Stranded Unimputed Genotyping Data
       * HRC Imputed Genotyping Data
   * Download:
     *  Subfolder: "QC Unimputed Genotyping Data", and read the READ_ME_1.txt file.
     *  Subfolder: "HRC Stranded Unimputed Genotyping Data", and read the READ_ME_2.txt file.
     *  Subfolder: "HRC Imputed Genotyping Data", and read the READ_ME_4.txt file.
   
