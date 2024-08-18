# McNamara-et-al-2023: Barcode Sequencing Analysis

## Project Overview

This repository contains the barcode sequencing analysis pipeline and data for the study "Gene dosage adaptations to mtDNA depletion and mitochondrial protein stress in budding yeast" by Joshua T. McNamara et al. (2023).

### Authors
- Joshua T. McNamara
- Yuhao Wang
- Jin Zhu
- Rong Li

**Affiliation:** Rong Li Lab, Johns Hopkins University

## Data Availability

Raw sequencing data are available at the [Sequence Read Archive (SRA)](https://www.ncbi.nlm.nih.gov/sra) under the following accession numbers:
- Project: PRJNA945832
- BioSample: SAMN33794339

## Installation
Clone the repository to your local machine:
```sh
git clone https://github.com/J-McNamara/McNamara-et-al-2023.git
cd McNamara-et-al-2023.git
```

## Data Preprocessing
1. Download the `fastq.gz` sequence data file from SRA to the `seq_data` directory.
2. Navigate to the `preprocessing` directory:
   ```
   cd preprocessing
   ```
3. Run the preprocessing script:
   ```
   bash preprocessing.sh
   ```
   This script indexes and counts the barcodes.

## Data Analysis
1. Open RStudio and set the working directory to the project root.
2. Open the R Markdown notebook: `analysis_notebook/barseq_notebook.Rmd`
3. Run the notebook to complete the data analysis.

## Directory Structure

```
McNamara-et-al-2023/
├── README.md
├── seq_data/
├── preprocessing/
│   └── preprocessing.sh
└── analysis_notebook/
    └── barseq_notebook.Rmd
```

## Contributing

We welcome contributions to improve the analysis pipeline. Please submit pull requests or open issues to discuss proposed changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Citation

If you use this data or analysis pipeline in your research, please cite:

Joshua T McNamara, Jin Zhu, Yuhao Wang, Rong Li, Gene dosage adaptations to mtDNA depletion and mitochondrial protein stress in budding yeast, G3 Genes|Genomes|Genetics, Volume 14, Issue 2, February 2024, jkad272, https://doi.org/10.1093/g3journal/jkad272


## Contact

For questions or clarifications, please contact [Josh McNamara](https://github.com/J-McNamara).
