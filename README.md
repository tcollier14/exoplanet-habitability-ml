# Calculating Exoplanet Habitability: Logistic and Ensemble Models

**Author:** Travis Collier  
**Project date:** October 18, 2026

## Overview

This project investigates the classification of exoplanets using statistical and machine-learning methods. Using a dataset of 3,950 exoplanets, the analysis explores whether planetary characteristics can be used to identify planets that fall within a defined habitable-zone criterion.

For this project, the target variable `in_habitable_zone` is defined using stellar insolation:

- `Yes`: `pl_insol > 0.25` and `pl_insol < 2.2`
- `No`: otherwise

This is a simplified insolation-based criterion, not a confirmation that a planet is actually habitable.

## Methods

The analysis explores the following techniques:

- Principal component analysis (PCA)
- K-means clustering
- Logistic regression
- Neural networks
- Decision trees
- Random forests
- XGBoost

The project uses R and Quarto to document the analysis and model results.

## Repository Contents

- **Quarto source (`.qmd`):** The research document containing the analysis, code, and discussion.

Additional files, including the rendered report and dataset information, may be added as the project is prepared for publication.

## Reproducibility

The analysis was developed in R using a Quarto document. Reproducing the results may require installing the R packages used in the source file and obtaining the dataset expected by the code.

## Limitations

The target variable is based on a defined stellar-insolation range. Classification results should therefore be interpreted as predictions of this criterion, rather than direct evidence of planetary habitability. Model performance also depends on the data, preprocessing, and evaluation methods used.

## License

No license has been specified yet. Until a license is added, the default copyright rules apply.
