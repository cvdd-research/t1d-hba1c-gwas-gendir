# T1D HbA1c GWAS (GENDIR)

Code accompanying a longitudinal genome-wide association study of HbA1c in pediatric type 1 diabetes, identifying an association at the *CNTFR* locus in the GENDIR cohort.

**Code will be added prior to journal submission**

## Overview

This repository will contain the analysis code used to:
- Perform quality control on genotype data
- Prepare longitudinal HbA1c phenotype data
- Run longitudinal mixed-effects models of HbA1c trajectories
- Conduct genome-wide association analysis
- Characterize the association at the *CNTFR* locus

## Repository structure

The analysis is organized as a [Quarto](https://quarto.org/) book. Structure may evolve as the project develops; see `_quarto.yml` for the current chapter organization.

```
_quarto.yml     Quarto book configuration
index.qmd       book landing page
*.qmd           analysis chapters
docs/           rendered output (if published) or extended notes
```

## Requirements

Analysis relies primarily on **R** (see `renv.lock` or `_environment` for package versions), with **bash** scripts for pipeline orchestration and **PLINK** for genotype data handling and association testing. Additional tools used are documented in the relevant `.qmd` chapters.

## Data availability

Genotype and phenotype data from the GENDIR cohort are not included in this repository due to privacy and consent restrictions. Access requests should be directed to Claire Vandiedonck.

## Citation

If you use this code, please cite:

> [Author list], "[Paper title]," *bioRxiv*, [year]. doi: [DOI to be added upon preprint availability]

A machine-readable citation is also provided in [`CITATION.cff`](./CITATION.cff).

## License

This code is released under the MIT License — see [`LICENSE`](./LICENSE) for details.

## Contact

For questions about the code or analysis, please open an issue or contact [name / email].
