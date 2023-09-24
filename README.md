# McNamara-et-al-2023

**Barcode sequencing analysis**

Joshua T. McNamara
Rong Li Lab
Johns Hopkins University  
2023

### Instructions
- Raw data are available at the [Sequence Read Archive](https://www.ncbi.nlm.nih.gov/sra) under accession number PRJNA945832, BioSample SAMN33794339.
- Download the fastq.gz sequence data file to the `seq_data` directory. Navigate to the `preprocessing` directory and run `preprocessing.sh`. This calls a pre-processing shell script that indexes and counts the barcodes.
- Open `analysis_notebook/barseq_notebook.Rmd` and run in RStudio to complete data analysis. 


### Publication info
Please cite the following work along with any use of this repository:
Joshua T. McNamara, Yuhao Wang, Jin Zhu, and Rong Li. Gene dosage adaptations to mtDNA depletion and mitochondrial protein stress in budding yeast. 2023.
