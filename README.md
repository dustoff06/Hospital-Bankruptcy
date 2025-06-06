# Code Branch: Predictive Factors of Hospital Bankruptcy

This branch contains the complete R Markdown analysis file used to develop, validate, and evaluate predictive models for hospital bankruptcy. The R Markdown script consolidates preprocessing, model development, diagnostics, and output generation into a single reproducible document.

## 📄 Contents

- `bankruptcy final 6 6.Rmd`: The full R Markdown file including all modeling steps.
- This file covers data loading, cleaning, exploratory data analysis, model fitting (including BRKFSST), and performance visualization.

## 🔧 R Environment

- **R version:** 4.5.0

## 📦 Required Libraries

Several R libraries are required and are *not commented out* in the script:

To install these, run:

```r
install.packages(c(
  "Amelia", "car", "caret", "corrplot", "dplyr", "formattable", "ggplot2",
  "ggcorrplot", "glmnet", "gridExtra", "Hmisc", "kableExtra", "kernlab",
  "knitr", "leaflet", "imbalance", "neuralnet", "pROC", "PRROC", "psych",
  "raster", "ResourceSelection", "rpart", "rpart.plot", "sp", "tidyverse"
))
```

## 🚀 How to Use

1. Ensure R version 4.5.0 is installed.
2. Open `analysis.Rmd` in RStudio.
3. Knit to HTML or run chunks interactively to reproduce the analysis.

## 📂 Related Branches

- `data`: contains training/testing datasets, lagged datasets, and interim datasets used for modeling.
- `paper`: contains the manuscript, appendices, and figures/tables for publication.

---

For questions, please contact the repository maintainer or visit the main `README.md` in the root directory.
