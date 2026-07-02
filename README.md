# T1D HbA1c GWAS (GENDIR)

Code accompanying a longitudinal genome-wide association study of HbA1c in pediatric type 1 diabetes, identifying an association at the *CNTFR* locus in the GENDIR cohort.

## Overview

This repository contains the analysis code used to:
- Perform quality control on genotype data
- Prepare longitudinal HbA1c phenotype data
- Run longitudinal mixed-effects models of HbA1c trajectories
- Conduct genome-wide association analysis
- Fine-map and characterize the association at the *CNTFR* locus

## Repository structure

```
config/     analysis configuration files
scripts/    analysis scripts, numbered in execution order
docs/       extended methods documentation
```

## Requirements

See `environment.yml` (or `requirements.txt`) for the full list of dependencies and versions used.

## Data availability

Genotype and phenotype data from the GENDIR cohort are not included in this repository due to privacy and consent restrictions. Access requests should be directed to [contact / data access committee — to complete].

## Citation

If you use this code, please cite:

> [Author list], "[Paper title]," *bioRxiv*, [year]. doi: [DOI to be added upon preprint availability]

A machine-readable citation is also provided in [`CITATION.cff`](./CITATION.cff).

## License

This code is released under the MIT License — see [`LICENSE`](./LICENSE) for details.

## Contact

For questions about the code or analysis, please open an issue or contact [name / email].
