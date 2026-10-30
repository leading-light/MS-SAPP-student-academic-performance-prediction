# MS-SAPP Experimental Results

This directory contains the experimental results generated for the **MS-SAPP (Student Academic Performance Prediction)** framework. The results are organized into two categories: General Results and Feature Ablation Results.

## Directory Structure

```text
results/
├── README.md
├── general/
│   ├── 01_All_Results
│   ├── 02_Classwise_Results
│   ├── 03_Top5_Per_Dataset
│   ├── 04_Overall_Composite_Ranking
│   ├── 05_Overall_Average_Rank
│   ├── 06_Top5_Overlap_Analysis
│   ├── 07_Final_Consensus_Ranking
│   ├── 08_Dataset_Ranking
│   ├── 09_Best_Model_Per_Dataset
│   ├── 10_Best_Dataset_Per_Model
│   ├── 11_Dataset_Summary
│   ├── 12_Overall_Winner
│   └── Benchmark_Results
└── ablation/
    ├── 01_Detailed_Ablation_Results
    ├── 02_Classwise_Ablation_Results
    ├── 03_Primary_Feature_Configuration_Summary
    ├── 04_Incremental_Feature_Improvement
    ├── 05_Feature_Configuration_Ranking
    ├── 06_Best_Feature_Configuration
    ├── 07_Classifier_Robustness_Summary
    ├── 08_Composite_Score_Matrix
    └── Feature_Ablation_Complete_Results
```

*Note: The filenames shown above omit file extensions for readability. The actual filenames and extensions should be retained in the repository.*

## 1. General Results

The `general/` directory contains the overall experimental results and comparative analyses.

| File | Description |
|---|---|
| `01_All_Results` | Consolidated experimental results across the evaluated models and datasets. |
| `02_Classwise_Results` | Class-level performance results for examining predictive performance across individual classes. |
| `03_Top5_Per_Dataset` | Top-five model selections for each dataset. |
| `04_Overall_Composite_Ranking` | Model rankings based on the overall composite scoring methodology. |
| `05_Overall_Average_Rank` | Comparative model rankings based on average rank. |
| `06_Top5_Overlap_Analysis` | Analysis of overlap among top-five model selections. |
| `07_Final_Consensus_Ranking` | Final consensus ranking of the evaluated models. |
| `08_Dataset_Ranking` | Comparative ranking of datasets according to the study's evaluation procedure. |
| `09_Best_Model_Per_Dataset` | Best-performing model identified for each dataset. |
| `10_Best_Dataset_Per_Model` | Dataset associated with the best observed performance of each model. |
| `11_Dataset_Summary` | Summary of the evaluated datasets and their results. |
| `12_Overall_Winner` | Summary identifying the overall winning model according to the defined selection criteria. |
| `Benchmark_Results` | Benchmark results for comparative evaluation. |

## 2. Feature Ablation Results

The `ablation/` directory contains results from experiments investigating the effects of different feature configurations on predictive performance.

| File | Description |
|---|---|
| `01_Detailed_Ablation_Results` | Detailed results from the feature ablation experiments. |
| `02_Classwise_Ablation_Results` | Class-level performance results for the evaluated feature configurations. |
| `03_Primary_Feature_Configuration_Summary` | Summary of the primary feature configurations evaluated in the study. |
| `04_Incremental_Feature_Improvement` | Analysis of performance changes associated with incremental feature additions or configurations. |
| `05_Feature_Configuration_Ranking` | Ranking of the evaluated feature configurations. |
| `06_Best_Feature_Configuration` | Results identifying the best feature configuration according to the study's selection criteria. |
| `07_Classifier_Robustness_Summary` | Summary of classifier performance across the evaluated feature configurations. |
| `08_Composite_Score_Matrix` | Composite scores for comparing the evaluated feature configurations. |
| `Feature_Ablation_Complete_Results` | Consolidated results from the feature ablation experiments. |

## 3. Purpose

These files provide supporting experimental evidence for analyzing predictive performance, comparing models, examining feature configurations, and evaluating model-selection outcomes within the MS-SAPP framework.

The general results focus on model and dataset comparisons, while the ablation results focus on the contribution of feature configurations to predictive performance.

## 4. Interpretation and Reproducibility

Results should be interpreted in conjunction with the methodology, datasets, preprocessing procedures, evaluation metrics, and experimental settings described in the research implementation.

The reported rankings and selected configurations reflect the criteria and procedures implemented in the experiments. Reproduction of the results requires the appropriate data, dependencies, configuration, and execution of the corresponding code.

For details about the framework, implementation, dependencies, and execution instructions, refer to the main repository `README.md` and the implementation in the `src/` directory.
