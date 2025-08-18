# optimalrcs_biomarker_ageing

This repository contains analysis scripts associated with the dissertation:

**"Data-driven modelling of ageing dynamics using the optimal reaction coordinate framework"**

**Project description:**

Molecular ageing clocks are models that employ machine learning (ML) techniques to estimate the biological age biological age of a sample. However, they are often trained on chronological age, which fails to account for differences in physiological status across individuals of the same chronological age. Additionally, they are often derived from cross-sectional data rather than longitudinal data, so fail to track changes in an individual over time. This project applies the optimal reaction coordinate (RC) framework to longitudinal DNA methylation data from the Swedish Adoption/Twin Study of Aging (SATSA) to predict biological age and compares these estimates to predictions made using standard molecular ageing clocks. The framework was extended to predict time to death, a valuable metric for longevity research. First, a surrogate end point was set to age 100 for all individuals and then the framework was reapplied after setting a surrogate end point for only individuals over 92 years. 

**Contents:**
- scripts/ – jupyter notebooks containing python for preprocessing, ML model selection and optimal RC framework application to predict biological age and time to death .
- README.md – Overview and instructions (this file).

**Note:** The SATSA dataset is available in the EMBL-EBL Array Express database under accession number E‐MTAB‐7309 (https://www.ebi.ac.uk/arrayexpress). 

