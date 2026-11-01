# Data

This directory contains the dataset files used in the **MS-SAPP (Multi-View and Multi-Stage Student Academic Performance Prediction) framework**.

## Dataset Description

The study uses a real-world student academic performance dataset comprising **1,021 student examination records from the University of Peshawar, Pakistan**. The dataset integrates three categories of information:

- **Academic features:** Information related to students' academic records and examination history.
- **Demographic features:** Student demographic characteristics.
- **Socio-economic features:** Institutional and socio-economic characteristics associated with students' educational backgrounds.

The target variable is `CD_Div`, representing the students' academic performance.

## Dataset Representations

To investigate the effects of data quality and target formulation on predictive performance, the study evaluates six dataset representations:

| Data condition | Three-class prediction | Two-class prediction |
|---|---|---|
| Original dataset | Included | Included |
| Duplicate-removed dataset | Included | Included |
| Outlier-filtered dataset | Included | Included |

These representations provide the basis for evaluating classifier performance under different data conditions and prediction tasks.

## Use in the MS-SAPP Framework

The dataset files are used by the main implementation notebook:

`src/St_Acd_Per_AutoML_Updated_Final.ipynb`

The notebook performs dataset loading, initial inspection, preprocessing, model evaluation, and the experiments described in the research study.

The data are also used in the feature-ablation experiments, which examine the contribution of academic, demographic, and socio-economic feature categories to student academic performance prediction.

## Data Access and Usage

Please refer to the dataset files included in this directory and the main implementation notebook for details of their use.

Users should cite the associated MS-SAPP research publication when using this dataset or reproducing the reported experiments. Publication and citation details will be added to the repository when available.

## Important Note

The dataset represents student-related educational information. Users must ensure that any redistribution, reuse, or further processing complies with applicable data-sharing permissions, institutional requirements, and privacy obligations.
