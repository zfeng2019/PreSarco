# PreSarco: Personalized Pre-Sarcopenia Risk Prediction

This repository contains the code for the PreSarco project, which is a self-evaluation tool designed to predict the risk of pre-sarcopenia. The project uses machine learning techniques for personalized risk assessment based on various health indicators.

### Data Access

The data used in this project is publicly available and can be accessed from the National Health and Nutrition Examination Survey (NHANES) website: [NHANES Data](https://www.cdc.gov/nchs/nhanes/index.htm).

### Project Files

The following R scripts are included in this repository:

- **01_load_libraries.Rmd**: Load required libraries
- **02_data_preprocessing.Rmd**: Data cleaning and preprocessing steps
- **03_data_interpolation.Rmd**: Handling missing data through interpolation
- **04_data_processing_and_partitioning.Rmd**: Data transformation and splitting into training, validation, and testing sets
- **05_smote_oversampling.Rmd**: Addressing class imbalance using SMOTE
- **06_model_run.Rmd**: Running machine learning models
- **07_LR_model_validation.Rmd**: Logistic regression model validation
- **08_delong_test_auc_comparison.Rmd**: Comparing AUC using DeLong test
- **09_SVM_shap_explanations.Rmd**: SHAP analysis for SVM model feature importance
- **10_external_svm_smote_evaluation.Rmd**: External testing and evaluation of the SVM model with SMOTE

### Hardware & Software Specifications

**Hardware:**

- CPU: 11th Gen Intel(R) Core(TM) i5-11400H @ 2.70GHz
- RAM: 16.0 GB
- GPU: NVIDIA GeForce RTX 3050 Laptop GPU
- OS: Windows 10 Pro

**Software:**

- **R**: Version 4.3.3
- **RStudio**: Version 2023.12.1+402

### Dependencies

The following R packages are required to run the code:

- **nhanesA**: 1.1
- **tidyverse**: 2.0.0
- **dplyr**: 1.1.4
- **plyr**: 1.8.9
- **knitr**: 1.46
- **foreign**: 0.8-86
- **survey**: 4.4-2
- **openxlsx**: 4.2.5.2
- **reshape2**: 1.4.4
- **do**: 2.0.0.0
- **caret**: 6.0-94
- **skimr**: 2.1.5
- **moments**: 0.14.1
- **ggplot2**: 3.5.0
- **tidyr**: 1.3.1
- **randomForest**: 4.7-1.1
- **PRROC**: 1.3.1
- **e1071**: 1.7-14
- **adabag**: 5.0
- **MASS**: 7.3-60.0.1
- **yardstick**: 1.3.1
- **gridExtra**: 2.3
- **pROC**: 1.18.5
- **class**: 7.3-22
- **ggpubr**: 0.6.0
- **ggprism**: 1.0.5
- **glmnet**: 4.1-8
- **FSelector**: 0.34
- **purrr**: 1.0.2
- **lightgbm**: 4.4.0
- **smotefamily**: 1.4.0
- **rBayesianOptimization**: 1.2.1
- **boot**: 1.3-30
- **outliers**: 0.15
- **ROSE**: 0.0-4
- **car**: 3.1-2
- **Hmisc**: 5.1-3
- **tableone**: 0.13.2
- **shapviz**: 0.9.3
- **lime**: 0.5.3
- **RSBID**: 0.0.2.0000
- **FNN**: 1.1.4
- **naniar**: 1.1.0.9000
- **VIM**: 6.2.2



### Acknowledgements

We would like to acknowledge the NHANES team for providing the public datasets used in this project.
