# PUBHHBP8899.02

Repository ID: 1284300775

## Project overview

This repository contains academic and research materials for the NIH/NIDA-funded dissertation project (R36):

"Examining the mediating effect of resilience on intersectional stigma and HIV prevention among people who inject drugs in rural Appalachia, Ohio."

The project uses quantitative methods and Structural Equation Modeling (SEM) to evaluate the impact of intersecting drug-use and HIV stigma (from everyday life and healthcare providers) on HIV testing utilization, and explores whether psychological resilience may act as a mediating protective factor.

## Key goals and scope

- Provide reproducible analysis scripts and model syntax for the SEM analyses.
- Store data cleaning and imputation scripts used to prepare analytic datasets.
- Archive model specifications (Mplus input files) and supporting documentation for transparency and reproducibility.
- Note: Protected human-subjects data are not included in this repository; see the Data Sharing section below.

## Primary languages & software

- Primary analysis and SEM: Mplus (WLSMV estimator for polychoric correlation matrices and SEM).
- Data cleaning, imputation, and pre-processing: R or SAS (R is commonly used; R scripts are included where available).
- Data capture system: REDCap (Research Electronic Data Capture) was used to collect study data.

This repository is a scientific data-analysis archive rather than an application. There is no runnable "app"; dependencies are limited to the statistical software and versions used to run the analysis scripts (Mplus, R, SAS). Specific software versions and package lists should be recorded in script headers or a separate environment file if desired.

## Highlighted files

- Mplus_SEM_Model.inp — Mplus input file containing the SEM model specification and estimator settings.
- Data_Cleaning_and_Imputation.R — R script(s) for data cleaning, missingness diagnostics, and multiple imputation.
- README.md — this file with project overview and data-sharing notes.

If these filenames differ in the repository, please tell me or I can scan the repo to list the exact paths.

## Getting started / Reproducing analyses

1. Obtain access to the analytic dataset (see Data Sharing below).
2. Run the data cleaning and imputation scripts (R/SAS) to create the analysis-ready dataset.
3. Run the Mplus input (.inp) files with Mplus to reproduce SEM results.

Example (informational only):

- This is a scientific data analysis repository. There is no application to run. Dependencies are limited to statistical analysis software (Mplus, R, SAS) used to execute the provided scripts and syntax files.

## Repository structure (suggested)

- /data/ - raw and processed data (not included in repo; see Data Sharing)
- /scripts/ - R, SAS, or other scripts for cleaning and imputation
- /mplus/ - Mplus input files and output logs
- /docs/ - study documentation, variable codebook, and protocol notes
- README.md - this file

Update this section if your repository uses a different layout.

## Data sharing and restrictions

In compliance with NIH guidelines and IRB/institutional policies, final unrestricted research datasets are only shared upon direct request under formal data-sharing agreements and with verified institutional IRB approval. Protected health information and participant-level data are not publicly available in this repository.

To request access to analytic data or additional materials, contact the principal investigator (below) and be prepared to provide a data use agreement and IRB approval documentation.

Contributions are restricted to authorized members of the research team unless explicit permission is granted by the PI and the institution.

## Contributions & contact

Principal Investigator / Contact:

- Stacy M. Endres-Dighe
- Doctoral Student, Epidemiology Division
- College of Public Health, The Ohio State University
- Email: Endres-dighe.1@buckeyemail.osu.edu

Contributions: Please contact the PI to discuss any proposed contributions. Unauthorized pull requests that attempt to add or share participant-level data will be rejected.

## License

Recommended options:

- MIT License — appropriate if you wish to permit reuse of code and text in the repository for general research and educational purposes.

OR

- No License / All Rights Reserved — choose this if institutional data-sharing restrictions or other considerations prohibit open licensing of the repository contents.

If you would like, I can add a LICENSE file with the MIT text, or explicitly mark the repo as All Rights Reserved. Tell me which option you prefer and I will add the license file.

## Other notes

- If you want me to fill in specific software versions, package lists (R packages with versions), or to scan the repository and automatically populate the Repository Structure section with actual paths and filenames, tell me and I'll proceed.
- I can also add badges (license, contact, or CI) or create a short CITATION file describing how to cite the work.

---

Last updated: 2026-06-29
